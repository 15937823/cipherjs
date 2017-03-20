[cipherjs][gh-repo]
===================

> Javascript implementation of simple Ciphers



## Installation

Install the package using `yarn`:

```bash
$ yarn add cipherjs
```

or `npm`:

```bash
$ npm install --save cipherjs
```



## Usage

Start by `require`-ing the module:

```js
const CipherJS = require('cipherjs');
```

It returns an `Object` of available ciphers, each with their own `encrypt` and `decrypt` methods:

```js
const Vigenere  = CipherJS.Vigenere;

Vigenere.encrypt('MY SECRET MESSAGE', 'MY SECRET KEY')
// YW KIEIIM WIQEYYI
```



## Command-line Application

`cipherjs` comes with a CLI app that lets you encrypt or decrypt data interactively. To use it,
install the package globally:

```bash
$ npm install -g cipherjs
```

and just execute `cipherjs` in your terminal:

```bash
$ cipherjs
```



## Contributing

 - [Fork][gh-fork], Enhance, Send PR
 - Lock issues with any bugs or feature requests
 - Implement something from Roadmap
 - Spread the word



## License

This package is available as open source under the terms of the [MIT License][gh-license].



  [gh-repo]:    https://github.com/sheharyarn/
  [gh-fork]:    https://github.com/sheharyarn/fork
  [gh-license]: https://github.com/sheharyarn/cipherjs/blob/master/LICENSE
