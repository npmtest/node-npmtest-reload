# npmtest-reload

#### basic test coverage for  reload (v1.1.2)  [![npm package](https://img.shields.io/npm/v/npmtest-reload.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-reload) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-reload.svg)](https://travis-ci.org/npmtest/node-npmtest-reload)

#### Node.js module to refresh and reload your code in your browser when your code changes. No browser plugins required.

[![NPM](https://nodei.co/npm/reload.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reload)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-reload/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-reload/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-reload/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-reload/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-reload/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-reload/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-reload/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-reload/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-reload/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-reload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-reload/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-reload/build/test-report.html](https://npmtest.github.io/node-npmtest-reload/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-reload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-reload/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-reload/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reload/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reload/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-reload/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-reload/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "reload",
    "version": "1.1.2",
    "description": "Node.js module to refresh and reload your code in your browser when your code changes. No browser plugins required.",
    "repository": {
        "type": "git",
        "url": "git@github.com:jprichardson/reload.git"
    },
    "keywords": [
        "reload",
        "refresh",
        "http",
        "express",
        "development"
    ],
    "author": "JP Richardson <jprichardson@gmail.com>",
    "contributors": [
        "Alexander J. Lallier <alexanderlallier@aol.com>"
    ],
    "license": "MIT",
    "dependencies": {
        "supervisor": "~0.11.0",
        "commander": "~2.9.0",
        "express": "~4.14.0",
        "cli-color": "~1.1.0",
        "open": "~0.0.5",
        "death": "~1.0.0",
        "ws": "~1.1.1",
        "minimist": "~1.2.0"
    },
    "devDependencies": {
        "standard": "^7.1.2"
    },
    "main": "./lib/reload.js",
    "scripts": {
        "standard": "standard",
        "test": "npm run standard"
    },
    "bin": {
        "reload": "./bin/reload"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
