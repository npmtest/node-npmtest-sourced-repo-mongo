# npmtest-sourced-repo-mongo

#### basic test coverage for  [sourced-repo-mongo (v0.3.12)](https://github.com/mateodelnorte/sourced-repo-mongo)  [![npm package](https://img.shields.io/npm/v/npmtest-sourced-repo-mongo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sourced-repo-mongo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sourced-repo-mongo.svg)](https://travis-ci.org/npmtest/node-npmtest-sourced-repo-mongo)

#### mongo data store and repository for sourced-style event sourcing models

[![NPM](https://nodei.co/npm/sourced-repo-mongo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sourced-repo-mongo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sourced-repo-mongo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sourced-repo-mongo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/test-report.html](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sourced-repo-mongo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sourced-repo-mongo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sourced-repo-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sourced-repo-mongo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sourced-repo-mongo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sourced-repo-mongo",
    "version": "0.3.12",
    "description": "mongo data store and repository for sourced-style event sourcing models",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "cconfig": "^0.0.0",
        "debug": "^0.8.1",
        "extend": "^1.2.1",
        "llog": "0.0.0",
        "lodash": "^2.4.1",
        "mongodb": "2.1.18",
        "sourced": "0.1.1"
    },
    "devDependencies": {
        "mocha": "^1.20.0",
        "should": "^4.0.0"
    },
    "scripts": {
        "test": "DEBUG= ./node_modules/.bin/mocha test -R spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mateodelnorte/sourced-repo-mongo.git"
    },
    "keywords": [
        "sourced",
        "eventsourcing",
        "eventsource",
        "event-source"
    ],
    "author": "mattwalters5@gmail.com",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/mateodelnorte/sourced-repo-mongo/issues"
    },
    "homepage": "https://github.com/mateodelnorte/sourced-repo-mongo"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
