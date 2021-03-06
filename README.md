js-lua: Run Lua from JavaScript
===============================

About
-----

JS-Lua is a JavaScript library which allows you to run Lua
code in browser (on the client-side). JS-Lua also provides
means for embedded Lua code to call JavaScript.

JS-Lua **no longer maintained**. Please use other Lua-in-browser implementation,
like [lua5.1.js](https://github.com/logiceditor-com/lua5.1.js).

See the copyright information in the file named `COPYRIGHT`.

Technologies
------------

-- Jill, Lua implementation in Java (MIT license, http://code.google.com/p/jillcode/)

-- Google Web Toolkit, used as Java to JavaScript compiler (Apache License 2.0, http://code.google.com/webtoolkit/).

-- aelua, used as GWT port of Jill (MIT license, http://code.google.com/p/aelua/).

Note to the library users: everything is built-in, you do not need any of tools listed here to use with JS-Lua.

API
---

(To be implemented)

### JS

 * `JSLua.callLua(functionName, args, ...) --> array of return values`

 * `JSLua.provideFile(path, file_contents_string)`

 * `JSLua.doFile(path)`

### Lua

 * `JSLua.callJS(functionName, args, ...) --> return value`

 * `JSLua.dofile(filename)`

 * `JSLua.loadfile(filename, chunkname)`
