# is-hell

> Return true if the given value is hell.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save is-hell
```

## Usage

```js
var isHell = require('is-hell');

isHell(0);
//=> false
isHell(null);
//=> false
isHell("2");
//=> false
isHell("hell");
//=> true
```