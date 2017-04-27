# npmtest-nodal

#### basic test coverage for  [nodal (v0.13.4)](https://github.com/keithwhor/nodal)  [![npm package](https://img.shields.io/npm/v/npmtest-nodal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nodal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nodal.svg)](https://travis-ci.org/npmtest/node-npmtest-nodal)

#### An API Server and Framework for node.js

[![NPM](https://nodei.co/npm/nodal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nodal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nodal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nodal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nodal/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nodal/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nodal/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nodal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nodal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nodal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nodal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nodal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nodal/build/test-report.html](https://npmtest.github.io/node-npmtest-nodal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nodal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nodal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nodal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nodal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nodal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Keith Horwood"
    },
    "bin": {
        "nodal": "cli/bin.js"
    },
    "bugs": {
        "url": "https://github.com/keithwhor/nodal/issues"
    },
    "dependencies": {
        "api-res": "~0.0.4",
        "async": "~1.5.2",
        "cmnd": "~0.1.0",
        "colors": "~1.1.0",
        "cross-spawn-async": "~2.1.6",
        "deep-equal": "~1.0.1",
        "dot": "~1.0.3",
        "dotenv": "^2.0.0",
        "fs-extra": "~0.26.4",
        "fxn": "~0.0.5",
        "i": "~0.3.4",
        "inquirer": "~0.11.3",
        "mime-types": "~2.1.9",
        "pg": "~4.5.5"
    },
    "description": "An API Server and Framework for node.js",
    "devDependencies": {
        "chai": "~3.5.0",
        "mocha": "~2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "94275f4bbffa5d97a3509962d4366d4b530525a8",
        "tarball": "https://registry.npmjs.org/nodal/-/nodal-0.13.4.tgz"
    },
    "gitHead": "386fe2b89acd817cfc54b4de19cba9f2a9273184",
    "homepage": "https://github.com/keithwhor/nodal",
    "keywords": [
        "framework",
        "api",
        "application",
        "branding",
        "server",
        "modular",
        "nodal"
    ],
    "license": "MIT",
    "main": "core/module.js",
    "maintainers": [
        {
            "name": "keithwhor"
        }
    ],
    "name": "nodal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/keithwhor/nodal.git"
    },
    "scripts": {
        "docs": "documentation build core/module.js -o docs -f html",
        "test": "mocha ./test/runner.js"
    },
    "version": "0.13.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
