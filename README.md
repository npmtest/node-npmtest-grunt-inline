# npmtest-grunt-inline

#### basic test coverage for  grunt-inline (v0.3.6)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-inline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-inline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-inline.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-inline)

#### Inlines img, script and link tags into the same file.

[![NPM](https://nodei.co/npm/grunt-inline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-inline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-inline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-inline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-inline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-inline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-inline/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-inline/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-inline/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-inline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-inline/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-inline/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-inline/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-inline/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-inline/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-inline/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-inline/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-inline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-inline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-inline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-inline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-inline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "程序猿小卡",
        "url": "https://github.com/chyingp"
    },
    "name": "grunt-inline",
    "description": "Inlines img, script and link tags into the same file.",
    "version": "0.3.6",
    "keywords": [
        "gruntplugin",
        "inline",
        "js",
        "css"
    ],
    "main": "inline",
    "repository": {
        "type": "git",
        "url": "https://github.com/chyingp/grunt-inline.git"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "devDependencies": {
        "grunt-contrib-nodeunit": "~0.1.2",
        "grunt-contrib-clean": "~0.4.0",
        "grunt-contrib-htmlmin": "~0.1.3",
        "grunt": "~0.4.0"
    },
    "dependencies": {
        "uglify-js": "2.4.1",
        "datauri": "~0.2.0",
        "clean-css": "1.1.7"
    },
    "scripts": {
        "test": "grunt test"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
