# npmtest-msee

#### basic test coverage for  msee (v0.3.3)  [![npm package](https://img.shields.io/npm/v/npmtest-msee.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-msee) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-msee.svg)](https://travis-ci.org/npmtest/node-npmtest-msee)

#### Msee is a command-line tool to read Markdown file in your terminal, and it's a library help your command-line software to output readable markdown content.

[![NPM](https://nodei.co/npm/msee.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/msee)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-msee/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-msee/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-msee/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-msee/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-msee/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-msee/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-msee/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-msee/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-msee/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-msee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-msee/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-msee/build/test-report.html](https://npmtest.github.io/node-npmtest-msee/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-msee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-msee/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-msee/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-msee/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-msee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-msee/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-msee/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-msee/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "msee",
    "version": "0.3.3",
    "description": "Msee is a command-line tool to read Markdown file in your terminal, and it's a library help your command-line software to output readable markdown content.",
    "main": "./lib/msee.js",
    "bin": "./bin/msee",
    "scripts": {
        "test": "env FORCE_COLOR=true tap --lines=85 test/**/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/firede/msee.git"
    },
    "dependencies": {
        "ansi-regex": "^2.0.0",
        "ansicolors": "^0.3.2",
        "cardinal": "^0.7.1",
        "chalk": "^1.1.1",
        "combined-stream-wait-for-it": "^1.1.0",
        "entities": "^1.1.1",
        "marked": "^0.3.5",
        "nopt": "^3.0.4",
        "table-header": "^0.2.2",
        "text-table": "^0.2.0",
        "through2": "^2.0.3",
        "wcstring": "^2.1.0",
        "xtend": "^4.0.0"
    },
    "keywords": [
        "markdown",
        "terminal",
        "reader",
        "console",
        "shell",
        "colors",
        "highlight"
    ],
    "author": "Firede <firede@firede.us>",
    "contributors": [
        "Martin Heidegger <martin.heidegger@gmail.com>"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/firede/msee/issues"
    },
    "devDependencies": {
        "stream-to-string": "^1.1.0",
        "tap": "^5.7.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
