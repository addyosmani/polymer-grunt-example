polymer-grunt-example
=====================

Polymer + Grunt

Supported commands
======================

* `grunt build` - creates a production build, including custom/polymer elements, hack to include bower components in HTML imports
* `grunt server` - preview and LiveReload/edit your Polymer application. Works on your custom elements too
* `grunt wcbuild` - specifically runs Vulcanizer. This is also currently executed as part of `grunt build` step.

Notes
======================

* Basic build process for project
* LiveReload + edit works for root, `/elements`, `/lib-elements`
* `grunt server` preview works
* `grunt build` works 
*  Simple `exec` of Vuncanizer tool via `grunt wcbuild`

Todos
=======================

* Wrap Vulcanizer into a build task
* Figure out a way to resolve dependency resolution issues for script tags/Bower components in HTML imports