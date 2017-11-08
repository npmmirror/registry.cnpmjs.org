# cnpm-registry

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: http://cnpmjs.org/badge/v/cnpm-registry.svg?style=flat-square
[npm-url]: http://cnpmjs.org/package/cnpm-registry
[travis-image]: https://img.shields.io/travis/cnpm/registry.svg?style=flat-square
[travis-url]: https://travis-ci.org/cnpm/registry
[codecov-image]: https://codecov.io/gh/cnpm/registry/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/cnpm/registry
[david-image]: https://img.shields.io/david/cnpm/registry.svg?style=flat-square
[david-url]: https://david-dm.org/cnpm/registry
[snyk-image]: https://snyk.io/test/npm/cnpm-registry/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/cnpm-registry
[download-image]: https://img.shields.io/npm/dm/cnpm-registry.svg?style=flat-square
[download-url]: https://npmjs.org/package/cnpm-registry

Private npm registry for Enterprise, base on eggjs

## QuickStart

<!-- add docs here for user -->

see [egg docs][egg] for more detail.

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### Deploy

```bash
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.


[egg]: https://eggjs.org
