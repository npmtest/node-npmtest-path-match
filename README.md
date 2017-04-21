# npmtest-path-match

#### basic test coverage for  path-match (v1.2.4)  [![npm package](https://img.shields.io/npm/v/npmtest-path-match.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-path-match) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-path-match.svg)](https://travis-ci.org/npmtest/node-npmtest-path-match)

#### wrapper around path-to-regexp for easy route parameters

[![NPM](https://nodei.co/npm/path-match.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/path-match)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-path-match/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-path-match/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-path-match/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-path-match/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-path-match/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-path-match/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-path-match/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-path-match/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-path-match/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-path-match/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-path-match/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-path-match/build/test-report.html](https://npmtest.github.io/node-npmtest-path-match/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-path-match/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-path-match/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-path-match/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-path-match/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-path-match/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-path-match/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-path-match/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-path-match/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "path-match",
    "description": "wrapper around path-to-regexp for easy route parameters",
    "version": "1.2.4",
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com",
        "twitter": "https://twitter.com/jongleberry"
    },
    "keywords": [
        "route",
        "router",
        "routing",
        "path",
        "regex",
        "regexp",
        "param",
        "params"
    ],
    "license": "MIT",
    "repository": "pillarjs/path-match",
    "dependencies": {
        "http-errors": "~1.4.0",
        "path-to-regexp": "^1.0.0"
    },
    "devDependencies": {
        "istanbul": "^0.4.2",
        "mocha": "^2.0.0"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "files": [
        "index.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
