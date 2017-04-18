# npmtest-sails

#### test coverage for  [sails (v0.12.13)](http://sailsjs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-sails.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails.svg)](https://travis-ci.org/npmtest/node-npmtest-sails)

#### API-driven framework for building realtime apps, using MVC conventions (based on Express and Socket.io)

[![NPM](https://nodei.co/npm/sails.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails/build/test-report.html](https://npmtest.github.io/node-npmtest-sails/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike McNeil"
    },
    "bin": {
        "sails": "./bin/sails.js"
    },
    "bugs": {
        "url": "http://github.com/balderdashy/sails/issues"
    },
    "dependencies": {
        "@sailshq/express": "^3.21.3",
        "@sailshq/lodash": "^3.10.2",
        "anchor": "~0.10.5",
        "async": "1.5.0",
        "captains-log": "1.0.0",
        "chalk": "1.1.3",
        "commander": "2.9.0",
        "compression": "1.6.2",
        "connect": "3.4.1",
        "connect-flash": "0.1.1",
        "consolidate": "0.14.1",
        "cookie": "0.1.2",
        "cookie-parser": "1.3.5",
        "cookie-signature": "1.0.6",
        "csurf": "1.9.0",
        "ejs": "2.3.4",
        "ejs-locals": "1.0.2",
        "express-handlebars": "3.0.0",
        "express-session": "1.14.2",
        "flaverr": "^1.0.0",
        "glob": "5.0.15",
        "grunt": "1.0.1",
        "grunt-cli": "1.2.0",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-coffee": "1.0.0",
        "grunt-contrib-concat": "1.0.1",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-cssmin": "1.0.1",
        "grunt-contrib-jst": "1.0.0",
        "grunt-contrib-less": "1.3.0",
        "grunt-contrib-uglify": "1.0.1",
        "grunt-contrib-watch": "1.0.0",
        "grunt-sails-linker": "~0.10.1",
        "grunt-sync": "0.5.2",
        "i18n": "0.8.1",
        "include-all": "^1.0.0",
        "merge-defaults": "~0.2.1",
        "method-override": "2.3.5",
        "mock-req": "0.2.0",
        "mock-res": "0.3.0",
        "parseurl": "1.3.1",
        "path-to-regexp": "1.5.3",
        "pluralize": "1.2.1",
        "prompt": "0.2.14",
        "rc": "1.0.1",
        "reportback": "~0.1.9",
        "rttc": "9.3.3",
        "sails-disk": "~0.10.9",
        "sails-generate": "~0.13.0",
        "sails-hook-orm": "~1.0.9",
        "sails-hook-sockets": "^0.13.9",
        "sails-stringfile": "~0.3.2",
        "sails-util": "~0.11.0",
        "semver": "5.1.0",
        "serve-favicon": "2.3.0",
        "serve-static": "1.10.2",
        "skipper": "~0.7.0",
        "uid-safe": "1.1.0",
        "walk": "2.3.9"
    },
    "description": "API-driven framework for building realtime apps, using MVC conventions (based on Express and Socket.io)",
    "devDependencies": {
        "benchmark": "1.0.0",
        "checksum": "0.1.1",
        "coffee-script": "1.9.1",
        "expect.js": "0.3.1",
        "fs-extra": "0.30.0",
        "istanbul": "0.4.1",
        "machinepack-fs": "^8.0.2",
        "machinepack-process": "^2.0.2",
        "mocha": "3.0.0",
        "portfinder": "0.4.0",
        "request": "2.68.0",
        "root-require": "0.3.1",
        "should": "5.2.0",
        "socket.io-client": "1.4.6",
        "supertest": "1.1.0",
        "tmp": "0.0.30"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "e060710dd1080bee11840f8f085e396f8aa08ff4",
        "tarball": "https://registry.npmjs.org/sails/-/sails-0.12.13.tgz"
    },
    "engines": {
        "node": ">= 0.10.0",
        "npm": ">= 1.4.0"
    },
    "gitHead": "594cd89d5989c9e4fcab094a39174793cf6128ed",
    "homepage": "http://sailsjs.org",
    "keywords": [
        "mvc",
        "web-framework",
        "express",
        "sailsjs",
        "sails.js",
        "REST",
        "API",
        "orm",
        "socket.io"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "balderdashy"
        },
        {
            "name": "particlebanana"
        },
        {
            "name": "sgress454"
        },
        {
            "name": "mikermcneil"
        }
    ],
    "name": "sails",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/sails.git"
    },
    "scripts": {
        "preinstall": "node ./lib/preinstall_npmcheck.js",
        "prepublish": "npm prune",
        "test": "mocha -b"
    },
    "version": "0.12.13"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
