# pretty-bytes [![Build Status](https://travis-ci.org/sindresorhus/pretty-bytes.svg?branch=master)](https://travis-ci.org/sindresorhus/pretty-bytes)

> Convert bytes to a human readable string: `1337` → `1.34 kB`

Useful for displaying file sizes for humans.

-

*Note that it uses base-10 (eg. kilobyte).  
[Read about the difference between kilobyte and kibibyte.](http://pacoup.com/2009/05/26/kb-kb-kib-whats-up-with-that/)*


## Install

Download [manually](https://github.com/sindresorhus/pretty-bytes/releases) or with a package-manager.

```bash
$ npm install --save pretty-bytes
```

```bash
$ bower install --save pretty-bytes
```

```bash
$ component install sindresorhus/pretty-bytes
```


## Usage

```js
prettyBytes(1337);
//=> '1.34 kB'

prettyBytes(100);
//=> '100 B'
```


## CLI

You can also use it as a CLI app by installing it globally:

```bash
$ npm install --global pretty-bytes
```

### Usage

```
$ pretty-bytes 1337
1.34 kB
```


## License

[MIT](http://opensource.org/licenses/MIT) © [Sindre Sorhus](http://sindresorhus.com)