@jeffstern/jeffsnpm

![npm](https://img.shields.io/npm/v/@jeffstern/jeffsnpm.svg)

I'm following a tutorial to make an npm package, but maybe I'll make a better one soon

## Install

```
$ npm install @jeffstern/jeffsnpm
```

## Usage

```js
const removeSpaces = require("@jeffstern/jeffsnpm");

removeSpaces("So much space!");
//=> "Somuchspace!"

removeSpaces(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
