# npmtest-node-workflow

#### basic test coverage for  node-workflow (v0.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-node-workflow.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-workflow) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-workflow.svg)](https://travis-ci.org/npmtest/node-npmtest-node-workflow)

#### Task orchestration API and runners

[![NPM](https://nodei.co/npm/node-workflow.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-workflow)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-workflow/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-workflow/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-workflow/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-workflow/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-workflow/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-workflow/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-workflow/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-workflow/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-workflow/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-workflow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-workflow/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-workflow/build/test-report.html](https://npmtest.github.io/node-npmtest-node-workflow/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-workflow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-workflow/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-workflow/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-workflow/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-workflow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-workflow/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-workflow/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-workflow/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-workflow",
    "description": "Task orchestration API and runners",
    "version": "0.1.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/kusor/node-workflow.git"
    },
    "author": "Pedro Palazón Candel <kusorbox@gmail.com> (http://www.joyent.com)",
    "contributors": [
        "Mark Cavage",
        "Trent Mick",
        "Josh Wilsdon",
        "Bryan Cantrill"
    ],
    "bin": {
        "workflow-api": "./bin/workflow-api",
        "workflow-runner": "./bin/workflow-runner"
    },
    "main": "lib/index.js",
    "dependencies": {
        "node-uuid": "1.3.3",
        "bunyan": "0.6.8",
        "async": "0.1.15",
        "restify": "1.0.0"
    },
    "scripts": {
        "test": "./node_modules/.bin/tap ./test/*.test.js"
    },
    "devDependencies": {
        "tap": "0.2.0"
    },
    "engines": {
        "node": ">=0.6"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
