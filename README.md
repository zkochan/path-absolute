> moved to https://github.com/zkochan/packages/tree/master/path-absolute

# path-absolute

> Resolves a path to an absolute path. Supports tilde

<!--@shields('npm', 'travis')-->
[![npm version](https://img.shields.io/npm/v/path-absolute.svg)](https://www.npmjs.com/package/path-absolute) [![Build Status](https://img.shields.io/travis/zkochan/path-absolute/master.svg)](https://travis-ci.org/zkochan/path-absolute)
<!--/@-->

## Installation

```sh
npm i -S path-absolute
```

## Usage

```js
const pathAbsolute = require('path-absolute')

pathAbsolute('~/foo')
//> '/home/zkochan/foo'

pathAbsolute('/foo/bar')
//> '/foo/bar'

pathAbsolute('./foo/bar', '/home')
//> '/home/foo/bar'
```

## API

### `pathAbsolute(path, [cwd]): string`

Resolves a path to an absolute path

## License

[MIT](LICENSE) © [Zoltan Kochan](https://www.kochan.io/)
