
# focus-element

[![Build status][travis-image]][travis-url]
[![Git tag][git-image]][git-url]
[![NPM version][npm-image]][npm-url]
[![Code style][standard-image]][standard-url]

Set the focus on a particular DOM element

## Installation

    $ npm install @f/focus-element

## Usage

```js
var focus = require('@f/focus-element')

function onClick (node) {
  focus(node.querySelector('input'))
}
```

## API

### focusElement(node)

- `node` - The DOM node you want to focus

**Returns:** void

## License

MIT

[travis-image]: https://img.shields.io/travis/micro-js/focus-element.svg?style=flat-square
[travis-url]: https://travis-ci.org/micro-js/focus-element
[git-image]: https://img.shields.io/github/tag/micro-js/focus-element.svg
[git-url]: https://github.com/micro-js/focus-element
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard
[npm-image]: https://img.shields.io/npm/v/@f/focus-element.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@f/focus-element
