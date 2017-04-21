# npmtest-react-shallow-testutils

#### basic test coverage for  [react-shallow-testutils (v2.0.0)](https://github.com/sheepsteak/react-shallow-testutils#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-shallow-testutils.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-shallow-testutils) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-shallow-testutils.svg)](https://travis-ci.org/npmtest/node-npmtest-react-shallow-testutils)

#### Replacement for TestUtils when using React's shallow rendering

[![NPM](https://nodei.co/npm/react-shallow-testutils.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-shallow-testutils)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-shallow-testutils/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-shallow-testutils/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-shallow-testutils/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/test-report.html](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-shallow-testutils/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-shallow-testutils",
    "version": "2.0.0",
    "description": "Replacement for TestUtils when using React's shallow rendering",
    "main": "lib/index.js",
    "scripts": {
        "clean": "rimraf lib/",
        "compile": "babel -d lib/ src/",
        "lint": "eslint --cache .",
        "prepublish": "npm run clean && npm run compile",
        "test": "node specs/support/jasmine"
    },
    "pre-commit": [
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sheepsteak/react-shallow-testutils.git"
    },
    "keywords": [
        "React",
        "testing",
        "components"
    ],
    "author": "Chris Shepherd <chris@chrisshepherd.me>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/sheepsteak/react-shallow-testutils/issues"
    },
    "homepage": "https://github.com/sheepsteak/react-shallow-testutils#readme",
    "devDependencies": {
        "babel-cli": "^6.7.5",
        "babel-core": "^6.7.6",
        "babel-eslint": "^6.0.2",
        "babel-plugin-transform-export-extensions": "^6.3.13",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.3.13",
        "eslint": "^2.7.0",
        "eslint-plugin-react": "^4.3.0",
        "jasmine": "^2.3.1",
        "pre-commit": "^1.1.1",
        "react": "^15.0.1",
        "react-addons-test-utils": "^15.0.1",
        "rimraf": "2.5.2"
    },
    "peerDependencies": {
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0"
    },
    "dependencies": {},
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
