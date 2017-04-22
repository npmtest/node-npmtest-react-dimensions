# npmtest-react-dimensions

#### basic test coverage for  [react-dimensions (v1.3.0)](https://github.com/digidem/react-dimensions#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-dimensions.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-dimensions) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-dimensions.svg)](https://travis-ci.org/npmtest/node-npmtest-react-dimensions)

#### React [higher-order component](https://gist.github.com/sebmarkbage/ef0bf1f338a7182b6775) to get dimensions of container

[![NPM](https://nodei.co/npm/react-dimensions.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-dimensions)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-dimensions/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dimensions/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-dimensions/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-dimensions/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-dimensions/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-dimensions/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-dimensions/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-dimensions/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-dimensions/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dimensions/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-dimensions/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-dimensions/build/test-report.html](https://npmtest.github.io/node-npmtest-react-dimensions/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-dimensions/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-dimensions/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-dimensions/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-dimensions/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-dimensions/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-dimensions/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-dimensions/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-dimensions/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gregor MacLennan"
    },
    "bugs": {
        "url": "https://github.com/digidem/react-dimensions/issues"
    },
    "dependencies": {
        "element-resize-event": "^2.0.4"
    },
    "description": "React [higher-order component](https://gist.github.com/sebmarkbage/ef0bf1f338a7182b6775) to get dimensions of container",
    "devDependencies": {
        "babel-cli": "^6.7.7",
        "babel-eslint": "^6.0.3",
        "babel-plugin-transform-class-properties": "^6.6.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babelify": "^7.2.0",
        "budo": "^8.2.1",
        "documentation": "^4.0.0-beta2",
        "eslint-config-standard": "^5.2.0",
        "eslint-config-standard-react": "^2.3.0",
        "eslint-plugin-react": "^5.0.1",
        "standard": "^6.0.8"
    },
    "directories": {},
    "dist": {
        "shasum": "f5dec8e7b84644a605a900cae0f4a6654acf4e9f",
        "tarball": "https://registry.npmjs.org/react-dimensions/-/react-dimensions-1.3.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "f55a28f0188ee7a546ecba1fa4f03bcd0013a794",
    "homepage": "https://github.com/digidem/react-dimensions#readme",
    "keywords": [
        "react",
        "dimensions",
        "width",
        "resize"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "gmaclennan"
        },
        {
            "name": "digidem"
        }
    ],
    "name": "react-dimensions",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/digidem/react-dimensions.git"
    },
    "scripts": {
        "build": "npm test && babel index.jsx -o index.js",
        "doc": "documentation readme index.jsx --section 'API'",
        "prepublish": "npm run build",
        "start": "budo example.jsx --live --open -- -t babelify",
        "test": "standard"
    },
    "standard": {
        "parser": "babel-eslint"
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
