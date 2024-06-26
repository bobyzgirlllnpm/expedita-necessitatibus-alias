# @bobyzgirlllnpm/expedita-necessitatibus-alias <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@bobyzgirlllnpm/expedita-necessitatibus-alias');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/expedita-necessitatibus-alias
[npm-version-svg]: https://versionbadg.es/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias.svg
[deps-svg]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias.svg
[deps-url]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias
[dev-deps-svg]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/expedita-necessitatibus-alias.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/expedita-necessitatibus-alias.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/expedita-necessitatibus-alias.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/expedita-necessitatibus-alias
[codecov-image]: https://codecov.io/gh/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@bobyzgirlllnpm/expedita-necessitatibus-alias
[actions-url]: https://github.com/bobyzgirlllnpm/expedita-necessitatibus-alias/actions
