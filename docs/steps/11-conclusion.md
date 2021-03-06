---
permalink: "/steps/11-conclusion.html"
title: "Conclusion"
layout: "post"
prev:
    url: "/steps/10.13-build.html"
    text: "Build the app"
---
<div class="explain">
At this point, you should have a workable <code>wasm</code> project, though you would need to stand up a server to actually get it running. I have completed both sides of the implementation, if wanted to run it locally you would need to run the following commands. 
</div>

```bash
$ git clone https://github.com/freemasen/wasm_tutorial
$ cd wasm_tutorial
$ ./build.sh
$ cargo run
```
<div class="explain">
That set of commands will build both the wasm and server implementations, you could then open your browser to <a href="http://localhost:8888"><code>localhost:8888</code></a> and see the application working. I also have deployed this to Heroku, if you just wanted to play around with it. Check out the network tab when you make any changes, you should see the request bodies all be random text (because your browser is trying to interpret the "hyper-text").
</div>

[live demo](https://todo-wasm.herokuapp.com/){:target="self"}
