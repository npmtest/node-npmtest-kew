# npmtest-kew

#### basic test coverage for  [kew (v0.7.0)](https://github.com/Medium/kew)  [![npm package](https://img.shields.io/npm/v/npmtest-kew.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kew) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kew.svg)](https://travis-ci.org/npmtest/node-npmtest-kew)

#### a lightweight promise library for node

[![NPM](https://nodei.co/npm/kew.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kew)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kew/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kew/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kew/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kew/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kew/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kew/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kew/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-kew/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-kew/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-kew/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-kew/build/test-report.html](https://npmtest.github.io/node-npmtest-kew/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-kew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kew/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-kew/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kew/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kew/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kew/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kew/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Jeremy Stanley <github@azulus.com> (https://github.com/azulus)",
        "Nick Santos <nick@medium.com>",
        "Xiao Ma <x@medium.com>"
    ],
    "bugs": {
        "url": "https://github.com/Medium/kew/issues"
    },
    "contributors": [],
    "dependencies": {},
    "description": "a lightweight promise library for node",
    "devDependencies": {
        "closure-npc": "0.1.5",
        "nodeunit": "0.9.0",
        "q": "0.9.7"
    },
    "directories": {},
    "dist": {
        "shasum": "79d93d2d33363d6fdd2970b335d9141ad591d79b",
        "tarball": "https://registry.npmjs.org/kew/-/kew-0.7.0.tgz"
    },
    "gitHead": "5773bcb8e6c27b531e366cd247b83b8cbf7bc989",
    "homepage": "https://github.com/Medium/kew",
    "keywords": [
        "kew",
        "promises"
    ],
    "license": "Apache-2.0",
    "main": "./kew.js",
    "maintainers": [
        {
            "name": "azulus"
        },
        {
            "name": "nicks"
        },
        {
            "name": "dpup"
        },
        {
            "name": "medium"
        },
        {
            "name": "xiao"
        },
        {
            "name": "chaosgame"
        }
    ],
    "name": "kew",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Medium/kew.git"
    },
    "scripts": {
        "test": "nodeunit test && closure-npc ./test/closure_test.js --jscomp_error=checkTypes"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
