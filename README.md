FxAnimation
===========

A simple library to export and animate Flash symbols in iOS / cocos2d, with included example.

Workflow:
* Create your animations in Flash as MovieClips with animated layers containing Graphic symbols. 
* Export animations as JSON + frame PNGs using included JSFL script.
* Convert PNGs into sprite sheets (use your own tools, I use http://www.codeandweb.com/texturepacker)
* Include animation JSON file(s) and sprite sheets in app bundle.
* Load textures, run complex multilayer animations on sprites using simple commands.

