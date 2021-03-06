# Frontie Bootstrap 4 - Front-end Boilerplate

Frontie Bootstrap 4 is a frontend boilerplate using Gulp for task automation.
Based on Bootstrap 4 enhanced with Twig.js, Autoprefixer and Browsersync.

## Core features

* [Gulp](http://gulpjs.com/)  
  For task automation

* [Bootstrap 4](http://getbootstrap.com/)  

* [Twig.js](https://github.com/twigjs/twig.js)  
  As a templating engine

* [Autoprefixer](https://www.npmjs.org/package/gulp-autoprefixer)  
  Parse CSS and add vendor prefixes to rules by Can I Use

* [Browsersync](https://www.browsersync.io/)  
  Time-saving synchronised browser testing

* [Github pages](https://www.npmjs.com/package/gulp-gh-pages)  
  Gulp plugin to publish contents to Github pages

* [Source Maps](https://www.npmjs.com/package/gulp-sourcemaps)

## Installation requirements
* [Node.js](https://nodejs.org/)
* [Gulp](http://gulpjs.com/)

## Quick start: Installation
**Download all the project dependencies:**
```sh
npm install / yarn
```

## Development: Tasks
**Build and watch:**
```sh
gulp
```

**Watch:**
```sh
gulp watch
```

**Generate a fresh build of your project to /dist folder:**
```sh
gulp build
```

**Publish contents from /dist folder to Github pages:**
```sh
gulp deploy
```

## Working Directories

* Source  
  All the files that you will be working with can be found at /src

* Production  
  Production files can be found at /dist

* CSS  
  The main file is located at /sass/custom.scss

* JS  
  The main file is located at /js/main.js

* JS  
  Third party JS libraries can be placed at /js/vendor

* Twig  
  Templates are located at /templates

## Notes

Based on [Frontie](https://github.com/tomaszbujnowicz/frontie)

## Copyright and license

Copyright 2018 Tomasz Bujnowicz under the [MIT license](http://opensource.org/licenses/MIT).
