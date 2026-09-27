Backends
================================

HaxeUI can target multiple frameworks (including native frameworks) by utilising a "backend system". This means that the logic of HaxeUI (inside `haxeui-core`) is separated from the code that actually performs the drawing, or — in the case of native GUIs — creates the native controls.

Backends come in two flavours: **Composite Backends** and **Native Backends**.

## Composite Backends

Composite backends usually utilise some type of drawing framework: the logic of the control is handled 100% inside HaxeUI and the drawing is delegated to the backend.

* [haxeui-html5](<000-Composite Backends/000-haxeui-html5.md>)
* [haxeui-kha](<000-Composite Backends/001-haxeui-kha.md>)
* [haxeui-openfl](<000-Composite Backends/002-haxeui-openfl.md>)
* [haxeui-flixel](<000-Composite Backends/003-haxeui-flixel.md>)
* [haxeui-nme](<000-Composite Backends/004-haxeui-nme.md>)
* [haxeui-heaps](<000-Composite Backends/005-haxeui-heaps.md>)
* [haxeui-raylib](<000-Composite Backends/006-haxeui-raylib.md>)

## Native Backends

Native backends differ from composite backends in that the creation of the actual component is delegated to the backend. This is useful for creating 100% native user interfaces while still leveraging the outward facing HaxeUI api.

* [haxeui-hxwidgets](<001-Native Backends/000-haxeui-hxwidgets.md>)
