# tslint-no-circular-imports [![Build Status][build]](https://circleci.com/gh/bcherny/tslint-no-circular-imports) [![npm]](https://www.npmjs.com/package/tslint-no-circular-imports) [![mit]](https://opensource.org/licenses/MIT)

[build]: https://img.shields.io/circleci/project/bcherny/tslint-no-circular-imports.svg?branch=master&style=flat-square
[npm]: https://img.shields.io/npm/v/tslint-no-circular-imports.svg?style=flat-square
[mit]: https://img.shields.io/npm/l/tslint-no-circular-imports.svg?style=flat-square

> [TSLint](https://palantir.github.io/tslint/) plugin to detect and warn about cicular imports

## Installation

```sh
npm install --save-dev tslint-no-circular-imports
```

## Usage

Add the following to your tslint.json:

```json
{
  "extends": ["tslint-no-circular-imports"]
}
```

## Running the tests

```sh
npm test
```

## License

MIT