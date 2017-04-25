# npmtest-vtop

#### basic test coverage for  [vtop (v0.5.7)](http://parall.ax/vtop)  [![npm package](https://img.shields.io/npm/v/npmtest-vtop.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vtop) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vtop.svg)](https://travis-ci.org/npmtest/node-npmtest-vtop)

#### Wow such top. So stats

[![NPM](https://nodei.co/npm/vtop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vtop)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vtop/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vtop/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vtop/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vtop/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vtop/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-vtop/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-vtop/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vtop/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vtop/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vtop/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vtop/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vtop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vtop/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vtop/build/test-report.html](https://npmtest.github.io/node-npmtest-vtop/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vtop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vtop/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vtop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vtop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vtop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vtop/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vtop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vtop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Hall"
    },
    "bin": {
        "vtop": "./bin/vtop.js"
    },
    "bugs": {
        "url": "https://github.com/MrRio/vtop/issues"
    },
    "dependencies": {
        "blessed": "0.1.81",
        "commander": "2.7.1",
        "drawille": "1.0.0",
        "glob": "5.0.2",
        "husky": "^0.11.9",
        "os-utils": "0.0.14",
        "read": "1.0.5",
        "safe-eval": "^0.3.0",
        "sudo": "1.0.3",
        "use-strict": "^1.0.1"
    },
    "description": "Wow such top. So stats",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "fff91000fac3a97a165f6f52dc253bce3d4d091e",
        "tarball": "https://registry.npmjs.org/vtop/-/vtop-0.5.7.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "182990627cf9ce89368de5baad786e16d5a0c974",
    "homepage": "http://parall.ax/vtop",
    "license": "MIT",
    "main": "app.js",
    "maintainers": [
        {
            "name": "mrjameshall"
        }
    ],
    "name": "vtop",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/MrRio/vtop.git"
    },
    "scripts": {
        "precommit": "standard",
        "test": "make test"
    },
    "standard": {
        "ignore": [
            "bin/vtop.js"
        ]
    },
    "version": "0.5.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
