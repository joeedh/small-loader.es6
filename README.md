# small-loader.es6
A simple, crude, transpiler that only supports ES6 module syntax.

# Introduction
Browser vendors seem in no hurry to implement ES6 modules, but they have started implementing other ES6 features.  Thus this little transpiler, which only transforms ES6 module syntax (import, export, etc).  Sourcemaps are supported.  Only works on Chrome (as of August 8th 2015).

## Issues
* Debugging breakpoints aren't working in Chrome.
* Only works in strict mode.



