# npmtest-metalsmith

#### test coverage for  [metalsmith (v2.3.0)](https://github.com/segmentio/metalsmith#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-metalsmith.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-metalsmith) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-metalsmith.svg)](https://travis-ci.org/npmtest/node-npmtest-metalsmith)

#### An extremely simple, pluggable static site generator.

[![NPM](https://nodei.co/npm/metalsmith.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/metalsmith)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-metalsmith/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-metalsmith/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-metalsmith/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-metalsmith/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-metalsmith/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-metalsmith/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-metalsmith/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-metalsmith/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-metalsmith/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-metalsmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-metalsmith/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-metalsmith/build/test-report.html](https://npmtest.github.io/node-npmtest-metalsmith/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-metalsmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-metalsmith/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-metalsmith/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-metalsmith/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-metalsmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-metalsmith/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-metalsmith/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-metalsmith/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "metalsmith": "bin/metalsmith",
        "_metalsmith": "bin/_metalsmith"
    },
    "bugs": {
        "url": "https://github.com/segmentio/metalsmith/issues"
    },
    "dependencies": {
        "absolute": "0.0.1",
        "chalk": "^1.1.3",
        "clone": "^1.0.2",
        "co-fs-extra": "^1.2.1",
        "commander": "^2.6.0",
        "gray-matter": "^2.0.0",
        "has-generators": "^1.0.1",
        "is": "^3.1.0",
        "is-utf8": "~0.2.0",
        "recursive-readdir": "^2.1.0",
        "rimraf": "^2.2.8",
        "stat-mode": "^0.2.0",
        "thunkify": "^2.1.2",
        "unyield": "0.0.1",
        "ware": "^1.2.0",
        "win-fork": "^1.1.1"
    },
    "description": "An extremely simple, pluggable static site generator.",
    "devDependencies": {
        "assert-dir-equal": "~1.0.1",
        "co-mocha": "^1.0.1",
        "coveralls": "^2.11.6",
        "istanbul": "^0.4.1",
        "metalsmith-drafts": "0.0.1",
        "metalsmith-markdown": "0.2.1",
        "mocha": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "833afbb5a2a6385e2d9ae3d935e39e33eaea5231",
        "tarball": "https://registry.npmjs.org/metalsmith/-/metalsmith-2.3.0.tgz"
    },
    "gitHead": "6596912d089e8e0a55b958f424822b192d03ecd8",
    "homepage": "https://github.com/segmentio/metalsmith#readme",
    "keywords": [
        "static",
        "file",
        "site",
        "website",
        "blog",
        "generator",
        "markdown",
        "jekyll",
        "wintersmith",
        "blacksmith"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ajedi32"
        },
        {
            "name": "dominicbarnes"
        },
        {
            "name": "ianstormtaylor"
        },
        {
            "name": "segment-admin"
        },
        {
            "name": "segmentio"
        },
        {
            "name": "woodyrew"
        }
    ],
    "name": "metalsmith",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/segmentio/metalsmith.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
