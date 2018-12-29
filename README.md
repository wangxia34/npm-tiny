# wangxia-tiny

[![](https://img.shields.io/npm/v/wangxia-tiny.svg)](https://github.com/wangxia34/npm-tiny)
[![](https://img.shields.io/bundlephobia/min/wangxia-tiny.svg)](https://www.npmjs.com/package/wangxia-tiny)

Removes all spaces from a string.

## Install

```
$ npm install wangxia-tiny
```

## Usage

```js
const tiny = require("wangxia-tiny");
tiny("So much space!");
//=> "Somuchspace!"
tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```


