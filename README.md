# npmtest-yuicompressor

#### basic test coverage for  yuicompressor (v2.4.8)  [![npm package](https://img.shields.io/npm/v/npmtest-yuicompressor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yuicompressor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yuicompressor.svg)](https://travis-ci.org/npmtest/node-npmtest-yuicompressor)

#### YUICompressor CLI and Node.js require

[![NPM](https://nodei.co/npm/yuicompressor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yuicompressor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yuicompressor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yuicompressor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yuicompressor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yuicompressor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yuicompressor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yuicompressor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yuicompressor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yuicompressor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yuicompressor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yuicompressor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yuicompressor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yuicompressor/build/test-report.html](https://npmtest.github.io/node-npmtest-yuicompressor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yuicompressor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yuicompressor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yuicompressor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yuicompressor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yuicompressor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yuicompressor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yuicompressor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yuicompressor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yuicompressor",
    "description": "YUICompressor CLI and Node.js require",
    "version": "2.4.8",
    "author": "Julien Lecomte <julien.lecomte@gmail.com>",
    "contributors": [
        {
            "name": "Dav Glass"
        },
        {
            "name": "Joey Smith"
        },
        {
            "name": "Stoyan Stefanov"
        }
    ],
    "bugs": {
        "url": "http://yuilibrary.com/projects/yuicompressor/newticket"
    },
    "devDependencies": {
        "yuitest": "*"
    },
    "keywords": [
        "yui",
        "compressor",
        "munger",
        "cssmin",
        "minify",
        "minification"
    ],
    "main": "./nodejs/index.js",
    "bin": {
        "yuicompressor": "./nodejs/cli.js"
    },
    "files": [
        "build/*.jar",
        "nodejs"
    ],
    "scripts": {
        "test": "yuitest ./nodejs_tests/tests.js"
    },
    "licenses": [
        {
            "type": "BSD",
            "url": "http://yuilibrary.com/license/"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/yui/yuicompressor"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
