# npmdoc-yargs-parser

#### api documentation for  yargs-parser (v5.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-yargs-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yargs-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yargs-parser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yargs-parser)

#### the mighty option parser used by yargs

[![NPM](https://nodei.co/npm/yargs-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yargs-parser)

- [https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yargs-parser",
    "version": "5.0.0",
    "description": "the mighty option parser used by yargs",
    "main": "index.js",
    "scripts": {
        "pretest": "standard",
        "test": "nyc mocha test/*.js",
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "release": "standard-version"
    },
    "repository": {
        "url": "git@github.com:yargs/yargs-parser.git"
    },
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
    "author": "Ben Coe <ben@npmjs.com>",
    "license": "ISC",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.12",
        "mocha": "^3.0.1",
        "nyc": "^10.0.0",
        "standard": "^8.0.0",
        "standard-version": "^4.0.0"
    },
    "dependencies": {
        "camelcase": "^3.0.0"
    },
    "files": [
        "lib",
        "index.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
