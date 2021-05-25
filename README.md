Hi, I'm Cosmin, a programmer from Bucharest. Most of my open source stuff is at [luapower.com](https://luapower.com) (with repos kept at [github.com/luapower](https://github.com/luapower)) which is why you don't see much coding activity in here even though my stats say otherwise.

I also keep a [scrapbook/blog/wiki](https://github.com/capr/scrapbook) in here and [a friend's old polaroids](https://rawgit.com/capr/oldbeat/master/index.html), if you're into that sort of thing.

## Stuff I've been working on

### Tools

[multigit](https://github.com/capr/mgit), a tool for checking out multiple git repositories overlaid onto the same directory, similar to a union filesystem, where each repository is a layer. Used as the package manager of luapower.com.

### Lua & LuaJIT

[sock](https://luapower.com/sock), a coroutine-based socket library with IOCP, epoll and kqueue for LuaJIT.

[coro](https://luapower.com/coro), adds symmetric coroutines to Lua and modifies standard coroutines to not break inside scheduled coroutine environments.

[resolver](https://luapower.com/resolver), a DNS resolver that queries multiple servers in parallel and uses the result that comes first.

[http](https://luapower.com/http), a pure-Lua HTTP client and server library that is independent of the socket library used for I/O.

[oo](https://luapower.com/oo), an object system with virtual properties and method overriding hooks for Lua.

[dynasm](https://luapower.com/dynasm), a modified version of [DynASM](https://corsix.github.io/dynasm-doc/) that allows generating, compiling, and running x86 and x86-64 assembly code directly from Lua.

[winapi](https://luapower.com/winapi), a binding of Windows API for LuaJIT, including windows, common controls and dialogs, message loop and system APIs.

[objc](https://luapower.com/objc), a full-featured Objective-C and Cocoa bridge for LuaJIT.

[nw](https://luapower.com/nw), a cross-platform library (Windows, Linux, Mac) for working with windows, graphics and input (like SDL but in Lua).

[ui](https://luapower.com/ui), an extensible UI toolkit written in Lua with widgets, layouts, styles and animations, leveraging my Terra work.

[path2d](https://luapower.com/path2d), a fast, full-featured 2D geometry library written in Lua which includes construction, drawing, measuring, hit testing and editing of 2D paths.

[cairo](https://luapower.com/cairo), a binding of the cairo 2D vector graphics library for LuaJIT.

[bmp](https://luapower.com/bmp), a Windows BMP file loading and saving module that handles all BMP file header versions, color depths and pixel formats.

[tweening](https://luapower.com/tweening), an animation library inspired by GSAP.

[thread](https://luapower.com/thread), a cross-platform threads and thread primitives for Lua.

[mustache](https://luapower.com/mustache), a full-spec mustache parser and bytecode-based renderer that produces the exact same output as mustache.js.

[webb](https://luapower.com/webb), a procedural web framework for Lua, which besides being a total oxymoron for the current generation of web developers, enables the creation  powerful web apps with extremely low amounts of code, zero tooling and zero offline processing ("building" as the kids call it), by leveraging the principle of convention-over-configuration.

[bundle](https://github.com/luapower/bundle), a small framework for bundling together LuaJIT, Lua modules, Lua/C modules, DynASM/Lua modules, C libraries, and other static assets (and even directory listings) into a single fat executable.

### Terra

[terra.layer](https://luapower.com/terra.layer), a HTML-like box-model layouting and rendering engine in Terra with a C API.

[terra.tr](https://luapower.com/terra.tr), a Unicode text layouting and rendering engine in Terra with a C API.

[terra.binder](https://luapower.com/terra.binder), Terra build system, C header generator and LuaJIT ffi binding generator.

### JavaScript

[x-widgets](https://luapower.com/x-widgets), a complete set of model-driven live-editable web components in pure JavaScript, including a super-fast editable virtual grid component with 3-way-binding and master-detail linking, useful for writing backoffice-type business apps.
