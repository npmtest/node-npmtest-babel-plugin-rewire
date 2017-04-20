# npmtest-babel-plugin-rewire

#### basic test coverage for  babel-plugin-rewire (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-plugin-rewire.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-plugin-rewire) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-plugin-rewire.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-plugin-rewire)

#### A babel plugin adding the ability to rewire module dependencies. This enables to mock modules for testing purposes.

[![NPM](https://nodei.co/npm/babel-plugin-rewire.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-rewire)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-plugin-rewire/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-plugin-rewire/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-plugin-rewire/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "babel-plugin-rewire",
    "version": "1.1.0",
    "description": "A babel plugin adding the ability to rewire module dependencies. This enables to mock modules for testing purposes.",
    "main": "lib/babel-plugin-rewire.js",
    "scripts": {
        "test": "./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests",
        "build": "./node_modules/.bin/babel src --out-dir lib",
        "prepublish": "./node_modules/.bin/babel src --out-dir lib"
    },
    "publishConfig": {
        "registry": "http://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/speedskater/babel-plugin-rewire.git"
    },
    "bugs": {
        "url": "https://github.com/speedskater/babel-plugin-rewire/issues"
    },
    "keywords": [
        "babel",
        "plugin",
        "rewire",
        "es6",
        "modules"
    ],
    "author": "r.binna@synedra.com",
    "contributors": [
        {
            "name": "Robert Binna"
        },
        {
            "name": "Peet Goddard"
        },
        {
            "name": "Eli White"
        },
        {
            "name": "Philip Spitzlinger"
        },
        {
            "name": "Gustaf Dalemar"
        }
    ],
    "license": "ISC",
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-plugin-syntax-async-functions": "^6.8.0",
        "babel-plugin-syntax-flow": "^6.8.0",
        "babel-plugin-syntax-jsx": "^6.8.0 ",
        "babel-plugin-transform-async-to-generator": "^6.8.0",
        "babel-plugin-transform-es2015-block-scoping": "^6.10.1 ",
        "babel-plugin-transform-es2015-template-literals": "^6.8.0",
        "babel-plugin-transform-es2015-typeof-symbol": "^6.8.0",
        "babel-plugin-transform-export-extensions": "^6.8.0",
        "babel-plugin-transform-flow-strip-types": "^6.18.0",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-plugin-transform-react-jsx": "^6.8.0",
        "babel-plugin-transform-regenerator": "^6.9.0",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-polyfill": "^6.9.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.11.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-runtime": "^6.11.6",
        "chai": "^3.5.0",
        "core-js": "^1.0.0",
        "expect.js": "^0.3.1",
        "mocha": "^2.2.4",
        "node-hook": "^0.1.0",
        "react": "^15.1.0",
        "react-dom": "^15.1.0",
        "regenerator-runtime": "^0.9.5",
        "should": "^9.0.2",
        "sinon": "^1.17.4"
    },
    "peerDependencies": {
        "babel-core": "^6.0.0",
        "babel-template": "^6.2.0",
        "babel-types": "^6.2.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
