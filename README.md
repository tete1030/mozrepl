MozRepl 
============

## Use in Zotero

1. Build
2. Install
3. Preferences -> Advanced -> General -> Config Editor
	- set `extensions.mozrepl.autoStart` to `true`
	- set `extensions.mozrepl.port` to port you want (default 4242)
4. `telnet 127.0.0.1 [port]`

## Important Notice

**Key technologies upon which MozRepl depends will be retired from the Mozilla platform in November 2017**. If you are relying on MozRepl, please investigate migration paths. The last known compatible version is Firefox 54.

## What is it

MozRepl is an extension for Firefox and other Mozilla applications. It listens on a TCP port for connections (by default localhost only) and responds with a shell where you can evaluate JavaScript code, in the browser context as well as in web pages.

## Demo

http://www.youtube.com/watch?v=5RSnHN6S52c

## Documentation

https://github.com/bard/mozrepl/wiki
