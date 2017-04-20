# npmtest-imdone

#### basic test coverage for  [imdone (v1.5.6)](http://piascikj.github.io/imdone/)  [![npm package](https://img.shields.io/npm/v/npmtest-imdone.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imdone) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imdone.svg)](https://travis-ci.org/npmtest/node-npmtest-imdone)

#### A task board and wiki in one!

[![NPM](https://nodei.co/npm/imdone.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imdone)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imdone/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imdone/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imdone/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imdone/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imdone/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imdone/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imdone/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imdone/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imdone/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imdone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imdone/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imdone/build/test-report.html](https://npmtest.github.io/node-npmtest-imdone/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imdone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imdone/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imdone/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imdone/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imdone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imdone/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imdone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imdone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jesse Piascik"
    },
    "bin": {
        "imdone": "bin/imdone.js"
    },
    "bugs": {
        "url": "https://github.com/piascikj/imdone/issues"
    },
    "dependencies": {
        "async": "~0.9.0",
        "body-parser": "*",
        "commander": "2.x",
        "cookie-parser": "~1.1.0",
        "debug": "~0.8.0",
        "express": "4.x",
        "handlebars": "~2.0.0-alpha.1",
        "imdone-core": "0.2.2",
        "keen.io": "^0.1.3",
        "lodash": "~2.4.1",
        "marked": "~0.3.1",
        "open": "0.0.x",
        "pkginfo": "0.3.0",
        "request": "2.x",
        "socket.io": "0.9.x",
        "underscore": "~1.6.0",
        "wrench": "1.5.x"
    },
    "description": "A task board and wiki in one!",
    "devDependencies": {
        "bower": "1.3.6",
        "grunt": "~0.4.1",
        "grunt-bower-task": "~0.3.2",
        "grunt-contrib-jshint": "~0.8.0",
        "tmp": "0.0.23"
    },
    "directories": {},
    "dist": {
        "shasum": "8d4d302bbc49c7fd29320078e03fdf7957854fe7",
        "tarball": "https://registry.npmjs.org/imdone/-/imdone-1.5.6.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "b341def0f4025cd1ccea60b9432a998fe69c43df",
    "homepage": "http://piascikj.github.io/imdone/",
    "keywords": [
        "todo",
        "scrum",
        "markdown",
        "kanban",
        "wiki",
        "code",
        "comments",
        "cli",
        "git",
        "task",
        "board",
        "task-board"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/piascikj/imdone/blob/master/LICENSE-MIT"
        }
    ],
    "main": "server/imdone",
    "maintainers": [
        {
            "name": "piascikj"
        }
    ],
    "name": "imdone",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/piascikj/imdone.git"
    },
    "scripts": {
        "start": "bin/imdone.js",
        "test": "grunt test --stack"
    },
    "subdomain": "piascikj.imdone",
    "version": "1.5.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
