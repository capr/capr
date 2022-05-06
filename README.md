Hi, I'm Cosmin, a programmer from Bucharest. 

At the moment I'm working on the [Allegory SDK](https://github.com/allegory-software/allegory-sdk), a self-contained cross-platform low-code programming environment for developing web-based database-driven business apps in LuaJIT and JavaScript.

My other big open source project is [luapower.com](https://luapower.com) with repos kept at [github.com/luapower](https://github.com/luapower).

I also keep a [blag](https://github.com/capr/blag) in here and [a friend's old polaroids](https://rawgit.com/capr/oldbeat/master/index.html), if you're into that sort of thing.

## Stuff I've been working on

### Tools

[multigit](https://github.com/capr/mgit), a tool for checking out multiple git repositories overlaid onto the same directory, similar to a union filesystem, where each repository is a layer. Used as the package manager of luapower (and the reason the repos in there don't keep documentation in `README.md`, but in `<module>.md`).

### Lua & LuaJIT

[luapower.com](https://luapower.com), a modular and portable LuaJIT toolkit (Windows, Linux ~~and Mac~~), with everything from native OS API bindings to portable sockets, threads,  windows, graphics, etc. Comes with documentation, binaries and the ability to create single-executable apps (desktop or command-line).

Here's some of its libraries in no particular order (full list on the website):

  * [winapi](https://luapower.com/winapi), a binding of Windows API, including windows, common controls and dialogs, message loop and system APIs.
  * [cairo](https://luapower.com/cairo), a binding of the cairo 2D vector graphics library.
  * [sock](https://luapower.com/sock), a coroutine-based socket library with IOCP, epoll and kqueue.
  * [http](https://luapower.com/http), a HTTP protocol library that is independent of the socket library used for I/O.
    * [http_client](https://luapower.com/http_client) with TLS, compression, persistent connections, pipelining, multiple client IPs, resource limits, auto-redirects, auto-retries, cookie jars, multi-level debugging, caching, cdata-buffer-based I/O. In short, your dream library for web scraping.
    * [http_server](https://luapower.com/http_server) with TLS, compression, persistent connections, pipelining, resource limits, multi-level debugging, buffer-based I/O.
  * [fs](https://luapower.com), a portable filesystem library that supports UTF-8 filenames, symlinks, hardlinks, pipes and mmapping on Windows, Linux and Mac.
  * [coro](https://luapower.com/coro), adds symmetric coroutines to Lua and modifies standard coroutines to not break inside scheduled coroutine environments.
  * [resolver](https://luapower.com/resolver), a DNS resolver that queries multiple servers in parallel and uses the result that comes first.
  * [glue](https://luapower.com/glue), an "assorted lengths of wire" library for Lua.
  * [oo](https://luapower.com/oo), an object system with virtual properties and method overriding hooks.
  * [dynasm](https://luapower.com/dynasm), a modified version of [DynASM](https://corsix.github.io/dynasm-doc/) that allows generating, compiling, and running x86 and x86-64 assembly code directly from Lua.
  * [objc](https://luapower.com/objc), a full-featured Objective-C and Cocoa bridge for LuaJIT.
  * [nw](https://luapower.com/nw), a cross-platform library (Windows, Linux, Mac) for working with windows, graphics and input (like SDL but in Lua).
  * [ui](https://luapower.com/ui), an extensible UI toolkit written in Lua with widgets, layouts, styles and animations (leverages my Terra work).
  * [path2d](https://luapower.com/path2d), a fast, full-featured 2D geometry library written in Lua which includes construction, drawing, measuring, hit testing and editing of 2D paths.
  * [bmp](https://luapower.com/bmp), a Windows BMP file loading and saving module that handles all BMP file header versions, color depths and pixel formats.
  * [tweening](https://luapower.com/tweening), an animation library inspired by GSAP.
  * [thread](https://luapower.com/thread), a cross-platform threads and thread primitives for Lua.
  * [webb](https://luapower.com/webb), a procedural web framework for Lua, which besides being something totally incomprehensible to the web kids today, makes building web apps fun again, with very low amounts of code, no tooling and no offline processing ("building" as the kids call it).
  * [mustache](https://luapower.com/mustache), a full-spec mustache parser and bytecode-based renderer that produces the exact same output as mustache.js.
  * [bundle](https://github.com/luapower/bundle), a small toolkit for bundling together LuaJIT, Lua modules, and other static assets into a single fat executable.

### Terra

Related to LuaJIT is [Terra](https://terralang.org), a low-level system programming language that is meta-programmed in Lua. Although it's a LLVM frontend, Terra's metaprograming features allow you to "lift it up" from its basic C semantics to C++ level capabilities and beyond, so you can code at different levels of abstraction as your problem demands without sacrificing performance, which is arguably the holy grail of all programming. Here's some of the more advanced stuff that I've done with it:

  * [terra.layer](https://luapower.com/terra.layer), a HTML-like box-model layouting and rendering engine with a C API.
  * [terra.tr](https://luapower.com/terra.tr), a Unicode text layouting and rendering engine with a C API.
  * [terra.binder](https://luapower.com/terra.binder), Terra build system, C header generator and LuaJIT ffi binding generator.

### JavaScript

[x-widgets](https://luapower.com/x-widgets), a collection of model-driven live-editable web components in pure JavaScript, including a fast editable virtual grid component with 3-way-binding and master-detail linking, useful for writing backoffice-type business apps. 

There's also a 3D math library for WebGL and a tiny WebGL2 wrapper in there but the documentation on that is sparse.
