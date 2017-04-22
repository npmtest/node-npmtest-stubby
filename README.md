# npmtest-stubby

#### basic test coverage for  [stubby (v4.0.0)](http://stub.by)  [![npm package](https://img.shields.io/npm/v/npmtest-stubby.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stubby) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stubby.svg)](https://travis-ci.org/npmtest/node-npmtest-stubby)

#### a lightweight server for stubbing external systems and endpoints

[![NPM](https://nodei.co/npm/stubby.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stubby)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stubby/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stubby/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stubby/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stubby/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stubby/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stubby/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stubby/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stubby/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stubby/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stubby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stubby/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stubby/build/test-report.html](https://npmtest.github.io/node-npmtest-stubby/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stubby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stubby/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stubby/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stubby/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stubby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stubby/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stubby/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stubby/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Mrak"
    },
    "bin": {
        "stubby": "bin/stubby"
    },
    "bugs": {
        "url": "https://github.com/mrak/stubby4node/issues"
    },
    "contributors": [
        {
            "name": "Eric Mrak"
        }
    ],
    "dependencies": {
        "async": ">=0.2.7",
        "ejs": ">=0.8.4",
        "isutf8": ">=1.0.11",
        "js-yaml": ">=1.0.1",
        "node-static": ">=0.6.4"
    },
    "description": "a lightweight server for stubbing external systems and endpoints",
    "devDependencies": {
        "buffer-equal": "^1.0.0",
        "eslint": "^1.2.1",
        "mocha": "^3.1.2",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "455122882133edd4ceb7371a80e0e0fb1ebec929",
        "tarball": "https://registry.npmjs.org/stubby/-/stubby-4.0.0.tgz"
    },
    "engine": {
        "node": ">=0.10"
    },
    "files": [
        "src",
        "package.json",
        "bin",
        "tls",
        "man",
        "webroot"
    ],
    "gitHead": "99c80c236ba55ca7d78268627375f74ebd43a0ac",
    "homepage": "http://stub.by",
    "keywords": [
        "server",
        "stub",
        "mock",
        "testing",
        "service",
        "endpoint",
        "http",
        "https",
        "api",
        "rest"
    ],
    "license": "Apache-2.0",
    "main": "src/main.js",
    "maintainers": [
        {
            "name": "afmrak"
        }
    ],
    "name": "stubby",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mrak/stubby4node.git"
    },
    "scripts": {
        "lint": "eslint src test",
        "start": "bin/stubby",
        "test": "npm run lint && mocha --recursive test --reporter dot"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
