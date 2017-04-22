# npmtest-connect-timeout

#### basic test coverage for  [connect-timeout (v1.8.0)](https://github.com/expressjs/timeout)  [![npm package](https://img.shields.io/npm/v/npmtest-connect-timeout.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-connect-timeout) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-connect-timeout.svg)](https://travis-ci.org/npmtest/node-npmtest-connect-timeout)

#### Request timeout middleware for Connect/Express

[![NPM](https://nodei.co/npm/connect-timeout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect-timeout)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-connect-timeout/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-timeout/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-connect-timeout/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-connect-timeout/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-connect-timeout/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-connect-timeout/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-connect-timeout/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-connect-timeout/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-connect-timeout/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-timeout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-connect-timeout/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-connect-timeout/build/test-report.html](https://npmtest.github.io/node-npmtest-connect-timeout/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-connect-timeout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-connect-timeout/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-connect-timeout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-connect-timeout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-connect-timeout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/timeout/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "http-errors": "~1.5.1",
        "ms": "0.7.2",
        "on-finished": "~2.3.0",
        "on-headers": "~1.0.1"
    },
    "description": "Request timeout middleware for Connect/Express",
    "devDependencies": {
        "eslint": "3.10.2",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.0",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4b74c58ad0303e069e4f417af388a058cfa3b839",
        "tarball": "https://registry.npmjs.org/connect-timeout/-/connect-timeout-1.8.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "31fde61ec2f9b454481e2eef0f34925dc805efb5",
    "homepage": "https://github.com/expressjs/timeout",
    "license": "MIT",
    "maintainers": [
        {
            "name": "aaron"
        },
        {
            "name": "defunctzombie"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "rauchg"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "connect-timeout",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/timeout.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot --check-leaks test/"
    },
    "version": "1.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
