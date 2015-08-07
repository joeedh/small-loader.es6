# small-loader.es6
A simple, crude transpiler that only supports ES6 module syntax.

# Introduction
Browser vendors seem in no hurry to implement ES6 modules, but they have started implementing other 
ES6 features.  Thus this little transpiler, which will compile ES6 module syntax into ES5 (using the
popular require.js module loader), but only the module syntax.

Sourcemaps are supported.

## Issues
* Only works on Chrome (as of August 8th 2015).
* Sourcemaps are sometimes off by one line
* Debugging breakpoints aren't working in Chrome.
* Only works in strict mode.
