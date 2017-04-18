# npmdoc-csvtojson

api documentation for  [csvtojson (v1.1.4)](http://keyangxiang.com/blog/csv2json/)  [![npm package](https://img.shields.io/npm/v/npmdoc-csvtojson.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-csvtojson) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csvtojson.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csvtojson)
#### A tool concentrating on converting csv data to JSON with customised parser supporting

[![NPM](https://nodei.co/npm/csvtojson.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csvtojson)

- [https://npmdoc.github.io/node-npmdoc-csvtojson/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csvtojson/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csvtojson/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Keyang Xiang"
    },
    "bin": {
        "csvtojson": "./bin/csvtojson"
    },
    "bugs": {
        "url": "https://github.com/Keyang/node-csvtojson/issues"
    },
    "contributors": [
        {
            "name": "Daniel Cohen",
            "url": "https://github.com/dcohenb"
        },
        {
            "name": "Trang",
            "url": "https://github.com/trangtungn"
        },
        {
            "name": "Matthias Lienau",
            "url": "https://github.com/atufkas"
        },
        {
            "name": "Alec Fenichel",
            "url": "https://github.com/fenichelar"
        },
        {
            "name": "Blake Blackshear",
            "url": "https://github.com/blakeblackshear"
        },
        {
            "name": "Dimitri Kennedy",
            "url": "https://github.com/roodboi"
        },
        {
            "url": "https://github.com/markwithers"
        },
        {
            "name": "Robert Porter",
            "url": "https://github.com/colarob"
        },
        {
            "name": "Jessica Good",
            "url": "https://github.com/jessicagood"
        },
        {
            "url": "https://github.com/jondayft"
        },
        {
            "name": "Dane Petersen",
            "url": "https://github.com/thegreatsunra"
        },
        {
            "name": "Jimi Ford",
            "url": "https://github.com/JimiHFord"
        },
        {
            "name": "Hocine Moukaideche",
            "url": "https://github.com/Off76"
        },
        {
            "name": "Keyang Xiang",
            "url": "https://github.com/Keyang"
        },
        {
            "name": "Ionică Bizău",
            "url": "https://github.com/IonicaBizau"
        },
        {
            "name": "Sean Lang",
            "url": "https://github.com/slang800"
        },
        {
            "name": "Tom Dodson",
            "url": "https://github.com/t3dodson"
        },
        {
            "name": "Jeff Johnson",
            "url": "https://github.com/jeffcjohnson"
        },
        {
            "name": "Amila Welihinda",
            "url": "https://github.com/amilajack"
        },
        {
            "name": "Zsolt R. Molnar",
            "url": "https://github.com/molnarzs"
        }
    ],
    "dependencies": {
        "lodash": "^4.17.3"
    },
    "description": "A tool concentrating on converting csv data to JSON with customised parser supporting",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-browserify": "^4.0.1",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-git": "^0.3.5",
        "grunt-madge": "0.0.6",
        "grunt-mocha-test": "^0.12.7",
        "grunt-newer": "^1.1.0",
        "imgur": "^0.1.5",
        "load-grunt-tasks": "^3.4.0",
        "minimist": "^1.2.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "8deafcd6e78dac01812a34ed022670e16d402fe7",
        "tarball": "https://registry.npmjs.org/csvtojson/-/csvtojson-1.1.4.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "590d5580348ede58e916277d8167f3f6e20f4219",
    "homepage": "http://keyangxiang.com/blog/csv2json/",
    "keywords": [
        "csv",
        "csv parser",
        "parse csv",
        "csvtojson",
        "json",
        "csv to json",
        "csv convert",
        "tojson",
        "convert csv to json",
        "csv-json"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "keyang"
        }
    ],
    "name": "csvtojson",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Keyang/node-csvtojson.git"
    },
    "scripts": {
        "test": "mocha ./test -R spec",
        "test-all": "mocha  ./test -R spec && CSV_WORKER=3 mocha ./test -R spec ",
        "test-debug": "mocha debug ./test -R spec"
    },
    "version": "1.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
