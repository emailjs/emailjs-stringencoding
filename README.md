# emailjs-stringencoding

[![Greenkeeper badge](https://badges.greenkeeper.io/emailjs/emailjs-stringencoding.svg)](https://greenkeeper.io/)

[![Build Status](https://travis-ci.org/emailjs/emailjs-stringencoding.png?branch=master)](https://travis-ci.org/emailjs/emailjs-addressparser) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)  [![ES6+](https://camo.githubusercontent.com/567e52200713e0f0c05a5238d91e1d096292b338/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f65732d362b2d627269676874677265656e2e737667)](https://kangax.github.io/compat-table/es6/)

This is a slimmed down version of [Joshua Bell's String Encoding Polyfill](https://github.com/inexorabletash/text-encoding) which only supports UTF-8, mainly to reach a reduced build size and to work across all JS runtimes.

## Usage

```
npm install --save emailjs-stringencoding
```

```js
import { encode, decode } from 'emailjs-stringencoding'
const uint8array = encode(string);
const string = decode(uint8array);
```
