# npmtest-pngjs

#### basic test coverage for  [pngjs (v3.0.1)](https://github.com/lukeapage/pngjs)  [![npm package](https://img.shields.io/npm/v/npmtest-pngjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pngjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pngjs.svg)](https://travis-ci.org/npmtest/node-npmtest-pngjs)

#### PNG encoder/decoder in pure JS, supporting any bit size & interlace, async & sync with full test suite.

[![NPM](https://nodei.co/npm/pngjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pngjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pngjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pngjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pngjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pngjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pngjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pngjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pngjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pngjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pngjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pngjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pngjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pngjs/build/test-report.html](https://npmtest.github.io/node-npmtest-pngjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pngjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pngjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pngjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pngjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pngjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pngjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pngjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pngjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/lukeapage/pngjs2/issues"
    },
    "contributors": [
        {
            "name": "Alexandre Paré"
        },
        {
            "name": "Gaurav Mali"
        },
        {
            "name": "Gusts Kaksis"
        },
        {
            "name": "Kuba Niegowski"
        },
        {
            "name": "Luke Page"
        },
        {
            "name": "Pietajan De Potter"
        },
        {
            "name": "Steven Sojka"
        },
        {
            "name": "liangzeng"
        },
        {
            "name": "Michael Vogt"
        },
        {
            "name": "Xin-Xin Wang"
        }
    ],
    "dependencies": {},
    "description": "PNG encoder/decoder in pure JS, supporting any bit size & interlace, async & sync with full test suite.",
    "devDependencies": {
        "buffer-equal": "1.0.0",
        "connect": "^3.4.0",
        "eslint": "^3.2.2",
        "istanbul": "^0.4.4",
        "phantomjs-prebuilt": "^2.1.7",
        "serve-static": "^1.10.0",
        "tap-dot": "^1.0.0",
        "tape": "^4.0.2"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "b15086ac1ac47298c8fd3f9cdf364fa9879c4db6",
        "tarball": "https://registry.npmjs.org/pngjs/-/pngjs-3.0.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "d64454721c8174d0c3e712c72144ccf615722768",
    "homepage": "https://github.com/lukeapage/pngjs",
    "keywords": [
        "PNG",
        "decoder",
        "encoder",
        "js-png",
        "node-png",
        "parser",
        "png",
        "png-js",
        "png-parse",
        "pngjs"
    ],
    "license": "MIT",
    "main": "./lib/png.js",
    "maintainers": [
        {
            "name": "agatronic"
        }
    ],
    "name": "pngjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/lukeapage/pngjs2.git"
    },
    "scripts": {
        "coverage": "istanbul -- cover node_modules/tape/bin/tape test/*-spec.js nolarge",
        "coverage-report": "npm run coverage && istanbul report html",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "lint": "eslint lib",
        "test": "npm run lint && tape test/*-spec.js | tap-dot && node test/run-compare"
    },
    "version": "3.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
