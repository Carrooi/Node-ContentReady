# content-ready

Listen for moment when content of element is ready (even with all images).

Depends on jquery, uses [q](https://npmjs.org/package/q) promise library.

This library is useful when you need to know when for example all images in some element are loaded.

## Installation

```
$ npm install content-ready
```

## Usage

```
var ready = require('content-ready');

ready($('#someRandomElement')).then(function(el) {
	console.log('all images were loaded.');
});
```

## Changelog

* 1.0.0
	+ First version