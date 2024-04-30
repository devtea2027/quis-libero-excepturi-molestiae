# Math.atanh <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.atanh` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @devtea2027/quis-libero-excepturi-molestiae
```

## Usage/Examples

```js
console.log(Math.atanh(-1)); // -Infinity
console.log(Math.atanh(0)); // 0
console.log(Math.atanh(0.5)); // 0.5493061443340548
console.log(Math.atanh(2)); // NaN
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2027/quis-libero-excepturi-molestiae
[npm-version-svg]: https://versionbadg.es/@devtea2027/quis-libero-excepturi-molestiae.svg
[deps-svg]: https://david-dm.org/devtea2027/quis-libero-excepturi-molestiae.svg
[deps-url]: https://david-dm.org/devtea2027/quis-libero-excepturi-molestiae
[dev-deps-svg]: https://david-dm.org/devtea2027/quis-libero-excepturi-molestiae/dev-status.svg
[dev-deps-url]: https://david-dm.org/devtea2027/quis-libero-excepturi-molestiae#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2027/quis-libero-excepturi-molestiae.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2027/quis-libero-excepturi-molestiae.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2027/quis-libero-excepturi-molestiae.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2027/quis-libero-excepturi-molestiae
[codecov-image]: https://codecov.io/gh/devtea2027/quis-libero-excepturi-molestiae/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/devtea2027/quis-libero-excepturi-molestiae/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/devtea2027/quis-libero-excepturi-molestiae
[actions-url]: https://github.com/devtea2027/quis-libero-excepturi-molestiae/actions
