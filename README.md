# GACP

[![Build Status][travis-image]][travis-url]
[![NPM Version][npm-version-image]][npm-url]
[![NPM Downloads][npm-downloads-image]][npm-url]
[![MIT License][license-image]][license-url]
[![Standard Version][standard-version-image]][standard-version-url]
[![Codecov][codecov-image]][codecov-url]

💬Git add, commit, push with conventional-changelog and gitmoji.

![GACP](./assets/images/gacp.gif)

## Installation

`npm i -g gacp`

## Usage

`gacp`

`gacp --help`

`gacp --no-push`

`gacp --emoji emoji`

## Configuration File

You can configure gacp via:

- A `gacp` property in `package.json`.
- A `.gacprc` file in JSON, YAML or CommonJS with or without extensions `.json`, `.yaml`, `.yml`, `.js`.
- A `gacp.config.js` file in CommonJS.

### Basic Configuration

With default configuration.

```json
{
  "push": true,
  "emoji": "code"
}
```

## Change log

[Change log](CHANGELOG.md)

## Contributing

[Contributing](CONTRIBUTING.md)

## Prior Art

- [gcmt](https://github.com/vivaxy/gcmt)
- [commitizen](https://github.com/commitizen/cz-cli)
- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog)
- [gitmoji-cli](https://github.com/carloscuesta/gitmoji-cli)
- [git-commit-cp](https://github.com/Dolov/git-commit-cp)
- [git-cz](https://github.com/streamich/git-cz)

[travis-image]: https://img.shields.io/travis/vivaxy/gacp.svg?style=flat-square
[travis-url]: https://travis-ci.org/vivaxy/gacp
[npm-version-image]: http://img.shields.io/npm/v/gacp.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/gacp
[npm-downloads-image]: https://img.shields.io/npm/dt/gacp.svg?style=flat-square
[license-image]: https://img.shields.io/npm/l/gacp.svg?style=flat-square
[license-url]: LICENSE
[standard-version-image]: https://img.shields.io/badge/release-standard%20version-brightgreen.svg?style=flat-square
[standard-version-url]: https://github.com/conventional-changelog/standard-version
[codecov-image]: https://img.shields.io/codecov/c/github/vivaxy/gacp.svg?style=flat-square
[codecov-url]: https://codecov.io/gh/vivaxy/gacp
