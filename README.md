# npmtest-bower-webpack-plugin

#### basic test coverage for  [bower-webpack-plugin (v0.1.9)](https://github.com/lpiepiora/bower-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-bower-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bower-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bower-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-bower-webpack-plugin)

#### Use bower with webpack

[![NPM](https://nodei.co/npm/bower-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bower-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bower-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bower-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bower-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bower-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bower-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bower-webpack-plugin",
    "version": "0.1.9",
    "description": "Use bower with webpack",
    "main": "lib/bower-plugin.js",
    "devDependencies": {
        "css-loader": "^0.9.0",
        "file-loader": "^0.8.1",
        "jsdom": "^1.0.3",
        "mocha": "1.21.x",
        "rimraf": "^2.2.8",
        "should": "4.0.x",
        "style-loader": "^0.8.1",
        "webpack": "^1.4.0"
    },
    "peerDependencies": {
        "webpack": ">=1.4.0"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "debug-test": "mocha --debug-brk --reporter spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/lpiepiora/bower-webpack-plugin.git"
    },
    "keywords": [
        "webpack",
        "plugin",
        "bower"
    ],
    "author": {
        "name": "Lukasz Piepiora",
        "url": "https://github.com/lpiepiora"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/lpiepiora/bower-webpack-plugin/issues"
    },
    "homepage": "https://github.com/lpiepiora/bower-webpack-plugin",
    "dependencies": {
        "loader-utils": "^0.2.5",
        "q": "^1.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
