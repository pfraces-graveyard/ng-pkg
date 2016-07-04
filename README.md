ng-pkg
======

Angular 1.x packaged in nodejs modules

Build system
------------

The purpose of a new build system is:

  * built on top of JavaScript tools (gulp build)
  * decouple all functionality in node modules
  * use browserify to generate a single bundle
  * publish angular node modules on npm (`ng-pkg`)

**All required changes in the angular codebase must be automated to keep in sync
with angular changes easily**

### Nice To Have

  * Create documentation by moving comments into markdown files

Why?
----

Having this build system working we will be able to:

  * use angular services in our unit tests using ng-mock
  * use angular functionality from node scripts
  * use angular functionality from the browser using browserify
  * choose which angular features to use and which not
  * create alternative distributions of angular
  * use node modules instead of angular modules/di

Roadmap
-------

### Angular core helpers

  * `copy`
  * `extend`
  * `merge`
  * `equals`
  * `element`
  * `forEach`
  * `noop`
  * `bind`
  * `toJson`
  * `fromJson`
  * `identity`
  * `isUndefined`
  * `isDefined`
  * `isString`
  * `isFunction`
  * `isObject`
  * `isNumber`
  * `isElement`
  * `isArray`
  * `isDate`
  * `lowercase`
  * `uppercase`

### Angular services

  * `compile.js`
  * `document.js`
  * `http.js`
  * `httpBackend.js`
  * `interpolate.js`
  * `interval.js`
  * `location.js`
  * `log.js`
  * `parse.js`
  * `q.js`
  * `rootScope.js`
  * `timeout.js`
  * `window.js`
