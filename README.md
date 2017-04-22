# npmtest-foreman

#### basic test coverage for  [foreman (v2.0.0)](http://strongloop.github.io/node-foreman/)  [![npm package](https://img.shields.io/npm/v/npmtest-foreman.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-foreman) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-foreman.svg)](https://travis-ci.org/npmtest/node-npmtest-foreman)

#### Node Implementation of Foreman

[![NPM](https://nodei.co/npm/foreman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/foreman)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-foreman/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-foreman/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-foreman/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-foreman/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-foreman/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-foreman/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-foreman/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-foreman/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-foreman/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-foreman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-foreman/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-foreman/build/test-report.html](https://npmtest.github.io/node-npmtest-foreman/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-foreman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-foreman/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-foreman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-foreman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-foreman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-foreman/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-foreman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-foreman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "foreman",
    "version": "2.0.0",
    "homepage": "http://strongloop.github.io/node-foreman/",
    "description": "Node Implementation of Foreman",
    "author": "StrongLoop, Inc.",
    "license": "MIT",
    "keywords": [
        "foreman",
        "upstart",
        "commandline",
        "env",
        "Procfile"
    ],
    "bin": {
        "nf": "nf.js"
    },
    "files": [
        "forward.js",
        "nf.js",
        "proxy.js",
        "lib/"
    ],
    "scripts": {
        "pretest": "jshint .",
        "test": "tap test/*.test.*"
    },
    "dependencies": {
        "commander": "~2.9.0",
        "http-proxy": "~1.11.1",
        "mustache": "^2.2.1",
        "shell-quote": "~1.4.2"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/strongloop/node-foreman.git"
    },
    "bugs": {
        "url": "https://github.com/strongloop/node-foreman/issues"
    },
    "engines": {
        "node": ">=0.6.9"
    },
    "preferGlobal": true,
    "devDependencies": {
        "chai": "~1.9.1",
        "jshint": "^2.6.3",
        "rimraf": "~2.2.8",
        "tap": "^0.7.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
