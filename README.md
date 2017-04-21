# npmtest-jquery.cookie

#### basic test coverage for  jquery.cookie (v1.4.1)  [![npm package](https://img.shields.io/npm/v/npmtest-jquery.cookie.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jquery.cookie) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jquery.cookie.svg)](https://travis-ci.org/npmtest/node-npmtest-jquery.cookie)

#### A simple, lightweight jQuery plugin for reading, writing and deleting cookies.

[![NPM](https://nodei.co/npm/jquery.cookie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jquery.cookie)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jquery.cookie/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jquery.cookie/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jquery.cookie/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jquery.cookie/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jquery.cookie/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jquery.cookie/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jquery.cookie/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jquery.cookie/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jquery.cookie/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jquery.cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jquery.cookie/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jquery.cookie/build/test-report.html](https://npmtest.github.io/node-npmtest-jquery.cookie/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jquery.cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jquery.cookie/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jquery.cookie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jquery.cookie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jquery.cookie",
    "version": "1.4.1",
    "description": "A simple, lightweight jQuery plugin for reading, writing and deleting cookies.",
    "main": "jquery.cookie.js",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "grunt"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/carhartl/jquery-cookie.git"
    },
    "author": "Klaus Hartl",
    "license": "MIT",
    "gitHead": "bd3c9713222bace68d25fe2128c0f8633cad1269",
    "readmeFilename": "README.md",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-contrib-jshint": "~0.4.0",
        "grunt-contrib-uglify": "~0.2.0",
        "grunt-contrib-qunit": "~0.2.0",
        "grunt-contrib-watch": "~0.3.0",
        "grunt-compare-size": "~0.4.0",
        "grunt-saucelabs": "~4.1.1",
        "grunt-contrib-connect": "~0.5.0",
        "gzip-js": "~0.3.0"
    },
    "volo": {
        "url": "https://raw.github.com/carhartl/jquery-cookie/v{version}/jquery.cookie.js"
    },
    "jspm": {
        "main": "jquery.cookie",
        "files": [
            "jquery.cookie.js"
        ],
        "buildConfig": {
            "uglify": true
        }
    },
    "jam": {
        "dependencies": {
            "jquery": ">=1.2"
        },
        "main": "jquery.cookie.js",
        "include": [
            "jquery.cookie.js"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
