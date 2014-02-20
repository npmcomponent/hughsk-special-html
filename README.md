*This repository is a mirror of the [component](http://component.io) module [hughsk/special-html](http://github.com/hughsk/special-html). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/hughsk-special-html`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# special-html [![Build Status](https://travis-ci.org/hughsk/special-html.png?branch=master)](https://travis-ci.org/hughsk/special-html)

Converts special UTF-8 characters in a string to their HTML escape code equivalents.

## Installation

With [NPM](http://npmjs.org):

``` bash
$ npm install special-html
```

Or [component](/component/component):

``` bash
$ component install hughsk/special-html
```

## Usage

``` javascript
var special = require('special-html')
  , original = '├── http-browserify@0.1.6 (concat-stream@0.0.8)'

console.log(special(original))
// &#9500;&#9472;&#9472; http-browserify@0.1.6 (concat-stream@0.0.8)
```
