# npmtest-testium

#### basic test coverage for  [testium (v3.3.1)](https://github.com/groupon-testium/testium)  [![npm package](https://img.shields.io/npm/v/npmtest-testium.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-testium) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-testium.svg)](https://travis-ci.org/npmtest/node-npmtest-testium)

#### Synchronous integration testing with Node.js bindings for WebDriver

[![NPM](https://nodei.co/npm/testium.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/testium)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-testium/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-testium/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-testium/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-testium/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-testium/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-testium/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-testium/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-testium/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-testium/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-testium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-testium/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-testium/build/test-report.html](https://npmtest.github.io/node-npmtest-testium/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-testium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-testium/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-testium/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-testium/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-testium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-testium/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-testium/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-testium/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sean Massa"
    },
    "bin": {
        "testium": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/groupon-testium/testium/issues"
    },
    "dependencies": {
        "assertive": "^1.4.0",
        "debug": "^2.1.0",
        "lodash": "^3.9.3",
        "mkdirp": "~0.5.0",
        "selenium-download": "^2.0.0",
        "testium-core": "^1.3.0",
        "testium-driver-sync": "^2.1.0",
        "testium-mocha": "^1.0.0"
    },
    "description": "Synchronous integration testing with Node.js bindings for WebDriver",
    "devDependencies": {
        "coffee-script": "1.9.3",
        "mocha": "^2.3.3",
        "npub": "^2.2.0",
        "rimraf": "^2.2.8",
        "testium-example-app": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "782b0038892c6b532da7efb78287edf50b09dcb5",
        "tarball": "https://registry.npmjs.org/testium/-/testium-3.3.1.tgz"
    },
    "engines": {
        "node": ">=0.10.16"
    },
    "gitHead": "41db3133368e9ec6d33230d819d1847b360871ce",
    "homepage": "https://github.com/groupon-testium/testium",
    "keywords": [
        "testing",
        "selenium",
        "webdriver"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/testium.js",
    "maintainers": [
        {
            "name": "smassa"
        },
        {
            "name": "jkrems"
        }
    ],
    "name": "testium",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org",
        "license": {
            "exclude": [
                "cli.js",
                "lib",
                "test"
            ]
        }
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/groupon-testium/testium.git"
    },
    "scripts": {
        "test": "make all"
    },
    "version": "3.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
