javascript-seed-project
=========================

[![Dependency Status](https://david-dm.org/dashed/javascript-seed-project.png)](https://david-dm.org/dashed/javascript-seed-project)

Seed git repo for JavaScript-based projects. Just clone and code.

Inspired by projects like [ultimate-seed](https://github.com/pilwon/ultimate-seed) and [angular-seed](https://github.com/angular/angular-seed). Unlike these seeds, this seed aims to be as generic and light as possible without catering to a partular application niche (e.g. angularjs-based apps).

With this seed, you should be able to:

1. Develop in JavaScript
2. Test in JavaScript
3. Build and bundle to JavaScript

Cycle steps one through three. Repeat as necessary.

**Note:** Ported from [coffeescript-seed-project](https://github.com/Dashed/coffeescript-seed-project)

Clone this git repo. Open 'gameFin.html' in a browser.

2.  Personalize the following files for your project:
    - `LICENSE`
    - `package.json`
    - `CHANGELOG.md`
    - `README.md`

    See [npm docs](https://npmjs.org/doc/json.html) for more on customizing `package.json`.

## gulp

Customize `gulpfile.js` as necessary. See [gulp docs](https://github.com/gulpjs/gulp).

## webpack

Customize `webpack.config.js` as necessary. Configuration are pretty much like command-line args to webpack.

Through the config, webpack will compile an unoptimized build via an entry file and place it within the `./dist/` folder.

Preset:

* `entry` - file to start bundling from
* `output.filename` - name of the unoptimized compiled file
* `output.library` - name of exported library (e.g. `MyAwesomeProject()`)
* `output.libraryTarget` - exporting library to global scope. In this case, preset to [`umd`](https://github.com/ForbesLindesay/umd) (Universal Module Definition), which enables library to be exported to browser, CommonJS,


Build
=====

1.  Run `gulp prod` to build the distributable.

    This places a minified js file in `./dist/` folder.

    The associated distributable source map file(s) is/are generated.


