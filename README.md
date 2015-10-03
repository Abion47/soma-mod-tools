# Soma-Mod-Tools

Atom plugin to aid with developing mods for SOMA. This plugin provides syntax coloring for the angelscript code files, and will also correctly apply syntax coloring to the various xml resources.

![Syntax-Highlighting Screenshot](https://raw.githubusercontent.com/Apjjm/soma-mod-tools/master/resources/screenshot.png)

Note:
This project is currently is using a fork of [symbols-view](https://github.com/atom/symbols-view) to provide symbols for .hps files. It seemed like a better choice, for now, to fork symbols-view while we test the extension and parsing rules for the grammar, rather than try to include a game specific file extension into a default atom-package. 
Ideally, when symbols-view has its tags provider service, we will use that.
