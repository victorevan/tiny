# @vh-victor/tiny

![https://github.com/victorevan/tiny](https://img.shields.io/npm/v/@vh-victor/tiny.svg)

Removes all spaces from a string.

## Install

```
$ npm install @vh-victor/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```