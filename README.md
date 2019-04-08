[![npm](https://img.shields.io/npm/v/@seannorton/tiny.svg)](https://www.npmjs.com/package/@seannorton/tiny) ![npm bundle size](https://img.shields.io/bundlephobia/min/@seannorton/tiny.svg?label=minified%20size)

Removes all spaces from a string

# Install

``` 
$ npm install @seannorton/tiny 
```

# Usage

```
const tiny = require('@seannorton/tiny');

tiny('So much space!');
//=> 'Somuchspace!'

tiny(1337);
//=>  Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

