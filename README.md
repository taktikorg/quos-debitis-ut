# @taktikorg/quos-debitis-ut <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Does the JS environment support named capture groups in regexes?

Returns `true` in node 10+, and equivalent engines.

## Example

```js
var hasNamedCaptures = require('@taktikorg/quos-debitis-ut');
var assert = require('assert');

assert.equal(typeof hasNamedCaptures(), 'boolean', 'returns true or false');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/quos-debitis-ut
[npm-version-svg]: https://versionbadg.es/inspect-js/@taktikorg/quos-debitis-ut.svg
[deps-svg]: https://david-dm.org/inspect-js/@taktikorg/quos-debitis-ut.svg
[deps-url]: https://david-dm.org/inspect-js/@taktikorg/quos-debitis-ut
[dev-deps-svg]: https://david-dm.org/inspect-js/@taktikorg/quos-debitis-ut/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@taktikorg/quos-debitis-ut#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/quos-debitis-ut.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/quos-debitis-ut.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/quos-debitis-ut.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/quos-debitis-ut
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikorg/quos-debitis-ut/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikorg/quos-debitis-ut/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikorg/quos-debitis-ut
[actions-url]: https://github.com/taktikorg/quos-debitis-ut/actions
