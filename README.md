# npmdoc-nconf

#### api documentation for  [nconf (v0.8.4)](https://github.com/flatiron/nconf#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nconf.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nconf) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nconf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nconf)

#### Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging.

[![NPM](https://nodei.co/npm/nconf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nconf)

- [https://npmdoc.github.io/node-npmdoc-nconf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nconf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nconf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nconf/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nconf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nconf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/flatiron/nconf/issues"
    },
    "dependencies": {
        "async": "^1.4.0",
        "ini": "^1.3.0",
        "secure-keys": "^1.0.0",
        "yargs": "^3.19.0"
    },
    "description": "Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging.",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "istanbul": "^0.4.1",
        "vows": "0.8.x"
    },
    "directories": {},
    "dist": {
        "shasum": "9502234f7ad6238cab7f92d7c068c20434d3ff93",
        "tarball": "https://registry.npmjs.org/nconf/-/nconf-0.8.4.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "3d4e58957878fab80fb3125784c04b615cf2f52e",
    "homepage": "https://github.com/flatiron/nconf#readme",
    "keywords": [
        "configuration",
        "key value store",
        "plugabble"
    ],
    "license": "MIT",
    "main": "./lib/nconf",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "jcrugzz"
        }
    ],
    "name": "nconf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/flatiron/nconf.git"
    },
    "scripts": {
        "cover": "istanbul cover vows -- test/*-test.js test/**/*-test.js  --spec",
        "coveralls": "cat coverage/lcov.info | coveralls",
        "test": "vows test/*-test.js test/**/*-test.js --spec"
    },
    "version": "0.8.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
