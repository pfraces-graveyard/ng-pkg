Angular 1.x core
================

For reference
-------------

  * `angularFiles.js`
  * `Gruntfile.js`

`src/`
------

  * `angular.bind.js`: call to `bindJQuery`
  * `Angular.js`: entry point, globals declaration, core helpers, **to be decoupled**
  * `angular.prefix`, `angular.suffix`: main wrapper
  * `AngularPublic.js`: `publishExternalAPI` definition
  * `apis.js`: `HashMap` definition
  * `jqLite.js`
  * `loader.js`: `setupModuleLoader` definition
  * `loader.prefix`, `loader.suffix`: wrap and call `setupModuleLoader`
  * `minErr.js`
  * `module.prefix`, `module.suffix`: angular module wrapper
  * `publishExternalApis.js`: call to `publishExternalApis`
  * `stringify.js`: `serializeObject` and `toDebugString` definitions

### Angular core helpers

  * `copy`
  * `extend`
  * `merge`
  * `equals`
  * `element`
  * `forEach`
  * `injector`
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

`src/auto/`
-----------

  * `injector.js`
