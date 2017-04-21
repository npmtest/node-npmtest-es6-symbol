# npmtest-es6-symbol

#### basic test coverage for  es6-symbol (v3.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-es6-symbol.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-es6-symbol) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-es6-symbol.svg)](https://travis-ci.org/npmtest/node-npmtest-es6-symbol)

#### ECMAScript 6 Symbol polyfill

[![NPM](https://nodei.co/npm/es6-symbol.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es6-symbol)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-es6-symbol/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-symbol/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-es6-symbol/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-es6-symbol/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-es6-symbol/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-es6-symbol/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-es6-symbol/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-es6-symbol/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-es6-symbol/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-symbol/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-es6-symbol/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-es6-symbol/build/test-report.html](https://npmtest.github.io/node-npmtest-es6-symbol/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-es6-symbol/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-es6-symbol/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-es6-symbol/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es6-symbol/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es6-symbol/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es6-symbol/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-es6-symbol/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-es6-symbol/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "es6-symbol",
    "version": "3.1.1",
    "description": "ECMAScript 6 Symbol polyfill",
    "author": "Mariusz Nowak <medyk@medikoo.com> (http://www.medikoo.com/)",
    "keywords": [
        "symbol",
        "private",
        "property",
        "es6",
        "ecmascript",
        "harmony",
        "ponyfill",
        "polyfill"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/es6-symbol.git"
    },
    "dependencies": {
        "d": "1",
        "es5-ext": "~0.10.14"
    },
    "devDependencies": {
        "tad": "~0.2.7",
        "xlint": "~0.2.2",
        "xlint-jslint-medikoo": "~0.1.4"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node ./node_modules/tad/bin/tad"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
