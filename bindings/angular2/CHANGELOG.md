CHANGELOG
====

1.0.0-rc.6 (2017-03-14)
----

### New Features

 * Added `OnsSelect` directive.
 * Added `nativeElement` getter function to access DOM element on all directives.

### Bug Fixes

 * Fixed `ons-input` caret position when using two-way binding.

### PEER-DEPENDENCY UPDATES

 * **onsenui**:
    * `^2.0.5` ----> `2.2.x`

1.0.0-rc.5 (2017-01-18)
----

### Bug Fixes

 * Fixed [#1725](https://github.com/OnsenUI/OnsenUI/issues/1725).
 * Changed to use NgZone manually when components is created dynamically.

1.0.0-rc.4 (2017-01-13)
----

### New Features

 * `angular2-onsenui` package no longer re-export `@angular/compile`.
 * Changed OnsenModule to re-export BrowserModule.

### Bug Fixes

 * Fixed [#1730](https://github.com/OnsenUI/OnsenUI/issues/1730).
 * Navigator params should accept any type.

### Misc

 * Updated Angular to 2.4.1.

### PEER-DEPENDENCY UPDATES

 * **@angular/\***:
    * `^2.1.2` ----> `^2.4.1`
 * **rxjs**:
    * `>=5.0.0-beta` ----> `^5.0.1`

1.0.0-rc.3 (2016-11-15)
----

### New Features

 * Changed to include `onsenui.d.ts` and removed unneeded `declare var ons: any;`.

### Bug Fixes

 * Fix `peerDependencies` to suppress `UNMET PEER DEPENDENCY` on `rxjs`.

### Misc

 * Updated Angular.

### PEER-DEPENDENCY UPDATES

 * **@angular/\***:
    * `^2.0.0` ----> `^2.1.2`
 * **rxjs**:
    * `^5.0.0-rc.1` ----> `>=5.0.0-beta`

1.0.0-rc.2 (2016-11-04)
----

### New Features

 * Added Angular 2 AOT support.

### Misc

 * Use WeakMap in pageLoader. (`OnsNavigator`, `OnsSplitter`, `OnsTabbar`)
 * Remove AfterViewInit. (`OnsSwitch`)
 * Updated umd-template for angular@2.0.0.

### BREAKING CHANGES

 * Replaced TypeScript 1.x d.ts files with 2.x d.ts files.
 * Dropped TypeScript 1.x support.

### PEER-DEPENDENCY UPDATES
 * **@angular/compiler-cli**:
    * none ----> `^2.0.0`
 * **rxjs**:
    * `^5.0.0-beta.12` ----> `^5.0.0-rc.1`

1.0.0-rc.1 (2016-09-15)
----

### Misc

 * Updated to angular-2.0.0.

### PEER-DEPENDENCY UPDATES

 * **@angular/common**:
    * `^2.0.0-rc.6` ----> `^2.0.0`
 * **@angular/compiler**:
    * `^2.0.0-rc.6` ----> `^2.0.0`
 * **@angular/forms**:
    * `^0.3.0` ----> `^2.0.0`
 * **@angular/core**:
    * `^2.0.0-rc.6` ----> `^2.0.0`
 * **@angular/platform-browser**:
    * `^2.0.0-rc.6` ----> `^2.0.0`
 * **@angular/platform-browser-dynamic**:
    * `^2.0.0-rc.6` ----> `^2.0.0`
 * **rxjs**:
    * `^5.0.0-beta.6` ----> `^5.0.0-beta.12`
 * **zone.js**:
    * `^0.6.12` ----> `^0.6.21`

1.0.0-rc.0 (2016-09-09)
----

### New Features

 * Added Angular2 API for `ons-alert-dialog`, `ons-popover`, `ons-dialog` and `ons-modal` components.
 * Changed component factories to provide "destroy" function to unload components.
 * Changed to provide umd bundle and its minimized bundle.

### Bug Fixes

 * Replaced deprecated ComponentResolver with ComponentFactoryResolver on some directives.

### Misc

 * Changed all examples to use NgModule.

### PEER-DEPENDENCY UPDATES

 * **@angular/common**:
    * `^2.0.0-rc.1` ----> `^2.0.0-rc.6`
 * **@angular/compiler**:
    * `^2.0.0-rc.1` ----> `^2.0.0-rc.6`
 * **@angular/core**:
    * `^2.0.0-rc.1` ----> `^2.0.0-rc.6`
 * **@angular/http**:
    * `^2.0.0-rc.1` ----> none
 * **@angular/platform-browser**:
    * `^2.0.0-rc.1` ----> `^2.0.0-rc.6`
 * **@angular/platform-browser-dynamic**:
    * `^2.0.0-rc.1` ----> `^2.0.0-rc.6`
 * **@angular/router**:
    * `^2.0.0-rc.1` ----> none
 * **@angular/router-deprecated**:
    * `^2.0.0-rc.1` ----> none
 * **@angular/upgrade**:
    * `^2.0.0-rc.1` ----> none

### BREAKING CHANGES

 * Removed `OnsPage`, `OnsCarousel`, `OnsAlertDialog` and `OnsPopover` directives.
 * Renamed `PageParams` to `Params`.

0.1.0-beta.9 (2016-08-05)
----

See [History for OnsenUI/bindings/angular2](https://github.com/OnsenUI/OnsenUI/commits/master/bindings/angular2).

0.1.0-beta.8 (2016-06-22)
----

0.1.0-beta.7 (2016-06-19)
----

0.1.0-beta.6 (2016-06-16)
----

0.1.0-beta.5 (2016-06-16)
----

0.1.0-beta.4 (2016-06-16)
----

0.1.0-beta.3 (2016-06-16)
----

0.1.0-beta.2 (2016-06-16)
----

0.1.0-beta.1 (2016-06-15)
----

0.1.0-beta.0 (2016-06-10)
----

<!--

0.0.1-dev.8 (2016-06-10)
----

0.0.1-dev.7 (2016-06-10)
----

0.0.1-dev.6 (2016-06-10)
----

0.0.1-dev.5 (2016-06-10)
----

0.0.1-dev.4 (2016-06-10)
----

0.0.1-dev.3 (2016-06-10)
----

0.0.1-dev.2 (2016-06-10)
----

0.0.1-dev.1 (2016-06-10)
----

0.0.1-dev.0 (2016-06-10)
----

-->
