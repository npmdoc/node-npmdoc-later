# npmdoc-later

#### api documentation for  later (v1.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-later.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-later) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-later.svg)](https://travis-ci.org/npmdoc/node-npmdoc-later)

#### Determine later (or previous) occurrences of recurring schedules

[![NPM](https://nodei.co/npm/later.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/later)

- [https://npmdoc.github.io/node-npmdoc-later/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-later/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-later/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-later/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-later/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-later/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "later",
    "version": "1.2.0",
    "description": "Determine later (or previous) occurrences of recurring schedules",
    "keywords": [
        "schedule",
        "occurrences",
        "recur",
        "cron"
    ],
    "author": "BunKat <bill@levelstory.com>",
    "repository": {
        "type": "git",
        "url": "git://github.com/bunkat/later.git"
    },
    "main": "index.js",
    "browserify": "index-browserify.js",
    "jam": {
        "main": "later.js",
        "shim": {
            "exports": "later"
        }
    },
    "devDependencies": {
        "smash": "~0.0.8",
        "mocha": "*",
        "should": ">=0.6.3",
        "jslint": "*",
        "uglify-js": "*",
        "benchmark": "*"
    },
    "license": "MIT",
    "scripts": {
        "test": "./node_modules/.bin/mocha test/**/*-test.js --reporter dot"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
