# npmtest-ps-tree

#### test coverage for  [ps-tree (v1.1.0)](http://github.com/indexzero/ps-tree)  [![npm package](https://img.shields.io/npm/v/npmtest-ps-tree.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ps-tree) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ps-tree.svg)](https://travis-ci.org/npmtest/node-npmtest-ps-tree)

#### Get all children of a pid

[![NPM](https://nodei.co/npm/ps-tree.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ps-tree)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ps-tree/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ps-tree/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ps-tree/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ps-tree/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ps-tree/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ps-tree/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ps-tree/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ps-tree/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ps-tree/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ps-tree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ps-tree/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ps-tree/build/test-report.html](https://npmtest.github.io/node-npmtest-ps-tree/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ps-tree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ps-tree/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ps-tree/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ps-tree/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ps-tree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ps-tree/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ps-tree/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ps-tree/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/indexzero/ps-tree/issues"
    },
    "contributors": [
        {
            "name": "Zhuohuan LI",
            "url": "https://github.com/zixia"
        }
    ],
    "dependencies": {
        "event-stream": "~3.3.0"
    },
    "description": "Get all children of a pid",
    "devDependencies": {
        "chalk": "^1.0.0",
        "codeclimate-test-reporter": "0.0.4",
        "cross-env": "^1.0.8",
        "istanbul": "^0.3.20",
        "pre-commit": "0.0.9",
        "precommit": "^1.1.5",
        "tape": "^3.0.3",
        "tree-kill": "^1.1.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "b421b24140d6203f1ed3c76996b4427b08e8c014",
        "tarball": "https://registry.npmjs.org/ps-tree/-/ps-tree-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "2d7ccd06b3c3cf58b386617e5405ab8c318e37e5",
    "homepage": "http://github.com/indexzero/ps-tree",
    "license": "MIT",
    "maintainers": [
        {
            "name": "indexzero"
        }
    ],
    "name": "ps-tree",
    "optionalDependencies": {},
    "pre-commit": [
        "coverage",
        "codeclimate"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/indexzero/ps-tree.git"
    },
    "scripts": {
        "_comment": "https://github.com/gotwarlost/istanbul#usage-on-windows",
        "codeclimate": "cross-env CODECLIMATE_REPO_TOKEN=84436b4f13c70ace9c62e7f04928bf23c234eb212c0232d39d7fb1535beb2da5 codeclimate < coverage/lcov.info",
        "coverage": "npm test && istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "test": "istanbul cover node_modules/tape/bin/tape test/test.js test/direct.js"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
