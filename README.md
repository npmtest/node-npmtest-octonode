# npmtest-octonode

#### basic test coverage for  [octonode (v0.7.11)](https://github.com/pksunkara/octonode#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-octonode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-octonode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-octonode.svg)](https://travis-ci.org/npmtest/node-npmtest-octonode)

#### nodejs wrapper for github v3 api

[![NPM](https://nodei.co/npm/octonode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/octonode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-octonode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-octonode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-octonode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-octonode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-octonode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-octonode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-octonode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-octonode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-octonode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-octonode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-octonode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-octonode/build/test-report.html](https://npmtest.github.io/node-npmtest-octonode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-octonode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-octonode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-octonode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-octonode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-octonode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-octonode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-octonode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-octonode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pavan Kumar Sunkara",
        "url": "http://pksunkara.github.com"
    },
    "bugs": {
        "url": "https://github.com/pksunkara/octonode/issues"
    },
    "dependencies": {
        "deep-extend": "^0.4.1",
        "randomstring": "^1.1.5",
        "request": "^2.72.0"
    },
    "description": "nodejs wrapper for github v3 api",
    "devDependencies": {
        "coffee-script": "^1.12.4",
        "nock": "^8.0.0",
        "vows": "^0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9855e590e384f3f913af31ae756f5a69b3b29e2c",
        "tarball": "https://registry.npmjs.org/octonode/-/octonode-0.7.11.tgz"
    },
    "engines": {
        "node": ">0.4.11"
    },
    "gitHead": "1c2e518186ccbb73d40b676d519be8fb5353265b",
    "homepage": "https://github.com/pksunkara/octonode#readme",
    "keywords": [
        "wrapper",
        "api",
        "v3",
        "github"
    ],
    "license": "MIT",
    "main": "./lib/octonode",
    "maintainers": [
        {
            "name": "pksunkara"
        }
    ],
    "name": "octonode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pksunkara/octonode.git"
    },
    "scripts": {
        "lib": "./node_modules/coffee-script/bin/cake lib",
        "test": "vows --spec $(find test -name '*.js')",
        "watch": "./node_modules/coffee-script/bin/cake watch"
    },
    "version": "0.7.11",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
