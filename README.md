@jeffstern/jeffsnpm

![npm](https://img.shields.io/npm/v/@jeffstern/jeffsnpm.svg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjeffstern%2Fjeffsnpm.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjeffstern%2Fjeffsnpm?ref=badge_shield)

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


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjeffstern%2Fjeffsnpm.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjeffstern%2Fjeffsnpm?ref=badge_large)