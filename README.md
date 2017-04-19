# npmtest-localforage

#### test coverage for  [localforage (v1.5.0)](https://github.com/localForage/localForage)  [![npm package](https://img.shields.io/npm/v/npmtest-localforage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-localforage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-localforage.svg)](https://travis-ci.org/npmtest/node-npmtest-localforage)

#### Offline storage, improved.

[![NPM](https://nodei.co/npm/localforage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/localforage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-localforage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-localforage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-localforage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-localforage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-localforage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-localforage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-localforage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-localforage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-localforage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-localforage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-localforage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-localforage/build/test-report.html](https://npmtest.github.io/node-npmtest-localforage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-localforage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-localforage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-localforage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-localforage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-localforage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-localforage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-localforage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-localforage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mozilla"
    },
    "bugs": {
        "url": "http://github.com/localForage/localForage/issues"
    },
    "dependencies": {
        "lie": "3.0.2"
    },
    "description": "Offline storage, improved.",
    "devDependencies": {
        "babel-core": "^6.5.1",
        "babel-loader": "^6.2.2",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-plugin-transform-es2015-modules-umd": "^6.5.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babelify": "^7.2.0",
        "browserify-derequire": "^0.9.4",
        "bundle-collapser": "^1.2.1",
        "cors": "^2.3.1",
        "grunt": "^0.4.2",
        "grunt-babel": "^6.0.0",
        "grunt-browserify": "^3.8.0",
        "grunt-contrib-concat": "^0.3.0",
        "grunt-contrib-connect": "^0.8.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^0.4.0",
        "grunt-contrib-watch": "^0.5.0",
        "grunt-es3-safe-recast": "^0.1.0",
        "grunt-jscs": "^1.5.0",
        "grunt-mocha": "^0.4.10",
        "grunt-rollup": "^0.6.2",
        "grunt-run": "^0.5.2",
        "grunt-saucelabs": "^5.1.2",
        "grunt-ts": "^6.0.0-beta.11",
        "grunt-webpack": "^1.0.11",
        "load-grunt-tasks": "^0.4.0",
        "mocha": "^1.18.2",
        "phantomjs": "^1.9.7-12",
        "rollupify": "^0.1.0",
        "script-loader": "^0.6.1",
        "typescript": "^2.0.3",
        "uglify-js": "^2.3.x",
        "webpack": "^1.12.13",
        "webpack-dev-server": "^1.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6b994e19b56611fa85df3992df397ac4ab66e815",
        "tarball": "https://registry.npmjs.org/localforage/-/localforage-1.5.0.tgz"
    },
    "gitHead": "e09ee3966862d50d101b6e2b442e4ad53b58663c",
    "homepage": "https://github.com/localForage/localForage",
    "keywords": [
        "indexeddb",
        "localstorage",
        "storage",
        "websql"
    ],
    "license": "Apache-2.0",
    "main": "dist/localforage.js",
    "maintainers": [
        {
            "name": "tofumatt"
        }
    ],
    "name": "localforage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/localForage/localForage.git"
    },
    "scripts": {
        "publish-docs": "node -e \"require('grunt').cli()\" null copy build-rules-html publish-rules",
        "test": "node -e \"require('grunt').cli()\" null test"
    },
    "typings": "typings/localforage.d.ts",
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
