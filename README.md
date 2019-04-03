@jeffstern/jeffsnpm

![npm](https://img.shields.io/npm/v/@jeffstern/jeffsnpm.svg)

Here's my readme!

## Install

```
$ npm install @jeffstern/jeffstern
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