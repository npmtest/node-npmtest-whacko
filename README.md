# npmtest-whacko

#### basic test coverage for  whacko (v0.19.1)  [![npm package](https://img.shields.io/npm/v/npmtest-whacko.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-whacko) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-whacko.svg)](https://travis-ci.org/npmtest/node-npmtest-whacko)

#### Cheerio (http://cheeriojs.github.io/cheerio/) fork that uses parse5 HTML-parser (https://github.com/inikulin/parse5) as an underlying platform

[![NPM](https://nodei.co/npm/whacko.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/whacko)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-whacko/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-whacko/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-whacko/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-whacko/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-whacko/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-whacko/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-whacko/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-whacko/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-whacko/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-whacko/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-whacko/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-whacko/build/test-report.html](https://npmtest.github.io/node-npmtest-whacko/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-whacko/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-whacko/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-whacko/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-whacko/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-whacko/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-whacko/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-whacko/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-whacko/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Matt Mueller <mattmuelle@gmail.com> (mattmueller.me)",
    "contributors": [
        {
            "name": "Ivan Nikulin",
            "url": "https://github.com/inikulin"
        }
    ],
    "name": "whacko",
    "description": "Cheerio (http://cheeriojs.github.io/cheerio/) fork that uses parse5 HTML-parser (https://github.com/inikulin/parse5) as an underlying platform ",
    "keywords": [
        "htmlparser",
        "jquery",
        "selector",
        "scraper",
        "parser",
        "html"
    ],
    "version": "0.19.1",
    "repository": {
        "type": "git",
        "url": "git://github.com/inikulin/whacko.git"
    },
    "main": "./index.js",
    "engines": {
        "node": ">= 0.6"
    },
    "dependencies": {
        "parse5": "^1.4.2",
        "css-select": "^1.2.0",
        "lodash": "^3.10.1",
        "domutils": "1.5"
    },
    "devDependencies": {
        "expect.js": "~0.3.1",
        "istanbul": "~0.2",
        "mocha": "*",
        "xyz": "~0.4.0"
    },
    "scripts": {
        "test": "mocha"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
