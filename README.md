# **aoyostudio.github.io**
# Introduction
This is the source repository for frontend of [**AOYO STUDIO**](http://www.aoyostudio.com).

# Usage
### Install
* clone repo: `$ git clone https://github.com/aoyostudio/aoyostudio.github.io.git`
* change directory: `$ cd aoyostudio.github.io/gulp`
* install gulp globally _(needed one time only, if not done before)_: `$ npm install --global gulp`
* install local npm dependencies: `$ npm install`  
_Refer to [fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions), if you are seeing EACCES or permissions errors._

### Run
* start gulp: `$ gulp`
* leave the terminal running with gulp

### Develop
* with gulp running already, start a new terminal
* change directory to source : `$ cd aoyostudio.github.io/src`
* make changes to a .html, .js, or .scss file
* gulp should watch and automatically rebuild
* reload browser to see changes

# Dependencies
This repository was created with following dependencies:
* `$ npm install --save-dev gulp gulp-sass`
* `$ npm install --save-dev gulp-inject`
* `$ bower init`
* `$ bower install --save bootstrap-sass`
* `$ npm install --save-dev wiredep`
* `$ npm install --save-dev del`

Following is the full list of dependencies:
* [**gulp**](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)
* gulp-sass
* gulp-inject
* wiredep
* del
* gulp-filter
* gulp-concat
* gulp-csso
* browser-sync
* bower

# About
[**AOYO STUDIO**](https://www.aoyostudio.com) provides tools and applications for self employed inviduals to save time and simplify life with smart applications that are custom made for your life and business.

# References
* [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
* [gulp](https://github.com/gulpjs/gulp)
* [bower bootstrap-sass](https://github.com/twbs/bootstrap-sass#c-bower)
* [Working with Sass, Bootstrap and Gulp](http://david-barreto.com/working-with-sass-bootstrap-and-gulp/)
