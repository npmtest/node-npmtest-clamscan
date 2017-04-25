# npmtest-clamscan

#### basic test coverage for  [clamscan (v0.8.4)](https://github.com/kylefarris/clamscan#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-clamscan.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clamscan) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clamscan.svg)](https://travis-ci.org/npmtest/node-npmtest-clamscan)

#### Use Node JS to scan files on your server with ClamAV's clamscan binary or clamdscan daemon. This is especially useful for scanning uploaded files provided by un-trusted sources.

[![NPM](https://nodei.co/npm/clamscan.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clamscan)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clamscan/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clamscan/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clamscan/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clamscan/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clamscan/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-clamscan/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-clamscan/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clamscan/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clamscan/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clamscan/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clamscan/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clamscan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clamscan/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clamscan/build/test-report.html](https://npmtest.github.io/node-npmtest-clamscan/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clamscan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clamscan/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clamscan/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clamscan/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clamscan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clamscan/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clamscan/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clamscan/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Farris",
        "url": "http://chomponllc.com"
    },
    "bugs": {
        "url": "https://github.com/kylefarris/clamscan/issues"
    },
    "contributors": [
        {
            "name": "dietervds"
        },
        {
            "name": "nicolaspeixoto"
        },
        {
            "name": "urg"
        },
        {
            "name": "SaltwaterC"
        }
    ],
    "dependencies": {
        "underscore": "1.5.x"
    },
    "description": "Use Node JS to scan files on your server with ClamAV's clamscan binary or clamdscan daemon. This is especially useful for scanning uploaded files provided by un-trusted sources.",
    "devDependencies": {
        "chai": "^2.3.0",
        "mocha": "^2.2.5",
        "request": "^2.57.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b5ec92bd7839f710e8820b92d19b649e22cb790e",
        "tarball": "https://registry.npmjs.org/clamscan/-/clamscan-0.8.4.tgz"
    },
    "engines": {
        "node": ">=0.10.13"
    },
    "gitHead": "d01c07f3f54fc48828ab31215d61747324f9c3d1",
    "homepage": "https://github.com/kylefarris/clamscan#readme",
    "keywords": [
        "clamav",
        "virus",
        "clamscan",
        "upload",
        "virus scanning",
        "clam",
        "clamd",
        "security"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kylefarris"
        },
        {
            "name": "saltwaterc"
        }
    ],
    "name": "clamscan",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/kylefarris/clamscan.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "0.8.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
