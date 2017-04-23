# npmtest-html2canvas

#### basic test coverage for  [html2canvas (v0.5.0-beta4)](http://html2canvas.hertzen.com)  [![npm package](https://img.shields.io/npm/v/npmtest-html2canvas.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html2canvas) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html2canvas.svg)](https://travis-ci.org/npmtest/node-npmtest-html2canvas)

#### Screenshots with JavaScript

[![NPM](https://nodei.co/npm/html2canvas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html2canvas)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html2canvas/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html2canvas/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html2canvas/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html2canvas/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html2canvas/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-html2canvas/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-html2canvas/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html2canvas/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html2canvas/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html2canvas/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html2canvas/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html2canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html2canvas/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html2canvas/build/test-report.html](https://npmtest.github.io/node-npmtest-html2canvas/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html2canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html2canvas/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html2canvas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html2canvas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html2canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html2canvas/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html2canvas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html2canvas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Niklas von Hertzen",
        "url": "http://hertzen.com"
    },
    "bugs": {
        "url": "https://github.com/niklasvh/html2canvas/issues"
    },
    "dependencies": {},
    "description": "Screenshots with JavaScript",
    "devDependencies": {
        "base64-arraybuffer": "^0.1.5",
        "bluebird": "^3.0.6",
        "browserify-derequire": "^0.9.4",
        "grunt": "^0.4.5",
        "grunt-browserify": "^4.0.1",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-connect": "^0.11.2",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-execute": "^0.2.2",
        "grunt-mocha-cli": "^1.12.0",
        "grunt-mocha-phantomjs": "^2.0.0",
        "html2canvas-proxy": "0.0.5",
        "humanize-duration": "^2.0.1",
        "lodash": "^3.10.1",
        "pngjs": "^2.2.0",
        "requirejs": "^2.1.20",
        "sauce-connect-launcher": "^0.13.0",
        "wd": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8282c62ac5fd78168f5702b5e4877157ca93f39e",
        "tarball": "https://registry.npmjs.org/html2canvas/-/html2canvas-0.5.0-beta4.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "83e9b85e1eb27993d48132af0fbfb4ee2f13c887",
    "homepage": "http://html2canvas.hertzen.com",
    "license": "MIT",
    "main": "dist/html2canvas.js",
    "maintainers": [
        {
            "name": "niklasvh"
        }
    ],
    "name": "html2canvas",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/niklasvh/html2canvas.git"
    },
    "scripts": {
        "sauceconnect": "tests/sauceconnect.js",
        "start": "grunt server",
        "test": "grunt travis --verbose"
    },
    "title": "html2canvas",
    "version": "0.5.0-beta4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
