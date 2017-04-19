# npmtest-csslint

#### test coverage for  [csslint (v1.0.5)](http://csslint.net/)  [![npm package](https://img.shields.io/npm/v/npmtest-csslint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csslint.svg)](https://travis-ci.org/npmtest/node-npmtest-csslint)

#### CSSLint

[![NPM](https://nodei.co/npm/csslint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csslint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csslint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csslint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csslint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csslint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csslint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csslint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csslint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csslint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csslint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csslint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csslint/build/test-report.html](https://npmtest.github.io/node-npmtest-csslint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csslint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csslint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csslint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csslint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicole Sullivan"
    },
    "bin": {
        "csslint": "./dist/cli.js"
    },
    "bugs": {
        "url": "https://github.com/CSSLint/csslint/issues"
    },
    "contributors": [
        {
            "name": "Nicholas C. Zakas"
        }
    ],
    "dependencies": {
        "clone": "~2.1.0",
        "parserlib": "~1.1.1"
    },
    "description": "CSSLint",
    "devDependencies": {
        "grunt": "~1.0.1",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-concat": "~1.0.0",
        "grunt-contrib-jshint": "~1.1.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-include-replace": "~5.0.0",
        "load-grunt-tasks": "~3.5.0",
        "time-grunt": "~1.4.0",
        "yuitest": "~0.7.9"
    },
    "directories": {},
    "dist": {
        "shasum": "19cc3eda322160fd3f7232af1cb2a360e898a2e9",
        "tarball": "https://registry.npmjs.org/csslint/-/csslint-1.0.5.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "dist/cli.js",
        "dist/csslint-node.js",
        "dist/csslint.js",
        "CHANGELOG",
        "LICENSE"
    ],
    "gitHead": "f57c84cf8c202828ae024a4d3ea08f4adceb187a",
    "homepage": "http://csslint.net/",
    "license": "MIT",
    "main": "./dist/csslint-node.js",
    "maintainers": [
        {
            "name": "cscott"
        },
        {
            "name": "nschonni"
        },
        {
            "name": "nzakas"
        },
        {
            "name": "stubbornella"
        },
        {
            "name": "xhmikosr"
        }
    ],
    "name": "csslint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/CSSLint/csslint.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
