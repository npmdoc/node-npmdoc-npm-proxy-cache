# npmdoc-npm-proxy-cache

#### basic api documentation for  [npm-proxy-cache (v1.0.1)](https://github.com/runk/npm-proxy-cache#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-proxy-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-proxy-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-proxy-cache.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-proxy-cache)

#### HTTP/HTTPS caching proxy for work with `npm` utility / registry

[![NPM](https://nodei.co/npm/npm-proxy-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-proxy-cache)

- [https://npmdoc.github.io/node-npmdoc-npm-proxy-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-proxy-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-proxy-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-proxy-cache/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-proxy-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-proxy-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dmitry Shirokov"
    },
    "bin": {
        "npm-proxy-cache": "./bin/npm-proxy-cache"
    },
    "bugs": {
        "url": "https://github.com/runk/npm-proxy-cache/issues"
    },
    "contributors": [
        {
            "name": "@someuser77"
        }
    ],
    "dependencies": {
        "commander": "^2.8.1",
        "log4js": "^0.6.26",
        "mkdirp": "^0.5.1",
        "request": "^2.81.0"
    },
    "description": "HTTP/HTTPS caching proxy for work with 'npm' utility / registry",
    "devDependencies": {
        "eslint": "^3.19.0",
        "github-publish-release": "^1.3.3",
        "mocha": "^3.2.0",
        "rimraf": "^2.6.1",
        "uuid": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "50c80e1b4ead2e780139e6d69c6e91e705e978de",
        "tarball": "https://registry.npmjs.org/npm-proxy-cache/-/npm-proxy-cache-1.0.1.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "69ff3a636e3892d7e0cf464071780dd0cffb03dd",
    "homepage": "https://github.com/runk/npm-proxy-cache#readme",
    "keywords": [
        "npm",
        "proxy",
        "registry",
        "cache",
        "proxy server",
        "forward proxy"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "runk"
        }
    ],
    "name": "npm-proxy-cache",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/runk/npm-proxy-cache.git"
    },
    "scripts": {
        "lint": "eslint -c .eslintrc .",
        "pretest": "npm run lint",
        "release": "scripts/release",
        "test": "mocha -R spec --recursive"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
