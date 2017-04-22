# npmdoc-yargs-parser

#### api documentation for  [yargs-parser (v5.0.0)](https://github.com/yargs/yargs-parser#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-yargs-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yargs-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yargs-parser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yargs-parser)

#### the mighty option parser used by yargs

[![NPM](https://nodei.co/npm/yargs-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yargs-parser)

- [https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Coe"
    },
    "bugs": {
        "url": "https://github.com/yargs/yargs-parser/issues"
    },
    "dependencies": {
        "camelcase": "^3.0.0"
    },
    "description": "the mighty option parser used by yargs",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.12",
        "mocha": "^3.0.1",
        "nyc": "^10.0.0",
        "standard": "^8.0.0",
        "standard-version": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "275ecf0d7ffe05c77e64e7c86e4cd94bf0e1228a",
        "tarball": "https://registry.npmjs.org/yargs-parser/-/yargs-parser-5.0.0.tgz"
    },
    "files": [
        "lib",
        "index.js"
    ],
    "gitHead": "2c95ba9e5ad3b8bb6248bf41f013d9bd3700d56f",
    "homepage": "https://github.com/yargs/yargs-parser#readme",
    "keywords": [
        "argument",
        "parser",
        "yargs",
        "command",
        "cli",
        "parsing",
        "option",
        "args",
        "argument"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe"
        },
        {
            "name": "nexdrew"
        }
    ],
    "name": "yargs-parser",
    "optionalDependencies": {},
    "repository": {
        "url": "git+ssh://git@github.com/yargs/yargs-parser.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "pretest": "standard",
        "release": "standard-version",
        "test": "nyc mocha test/*.js"
    },
    "version": "5.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
