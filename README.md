# @hishprorg/perferendis-minus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Does this JS environment support the `name` property on functions?

## Example

```js
var functionsHaveNames = require('@hishprorg/perferendis-minus');
var assert = require('assert');

assert.equal(functionsHaveNames(), true); // will be `false` in IE 6-8
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hishprorg/perferendis-minus
[npm-version-svg]: https://versionbadg.es/inspect-js/@hishprorg/perferendis-minus.svg
[deps-svg]: https://david-dm.org/inspect-js/@hishprorg/perferendis-minus.svg
[deps-url]: https://david-dm.org/inspect-js/@hishprorg/perferendis-minus
[dev-deps-svg]: https://david-dm.org/inspect-js/@hishprorg/perferendis-minus/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@hishprorg/perferendis-minus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/perferendis-minus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/perferendis-minus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/perferendis-minus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/perferendis-minus
[codecov-image]: https://codecov.io/gh/inspect-js/@hishprorg/perferendis-minus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@hishprorg/perferendis-minus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@hishprorg/perferendis-minus
[actions-url]: https://github.com/hishprorg/perferendis-minus/actions
