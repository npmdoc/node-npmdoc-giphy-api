# npmdoc-giphy-api

#### basic api documentation for  [giphy-api (v1.2.5)](https://github.com/austinkelleher/giphy-api)  [![npm package](https://img.shields.io/npm/v/npmdoc-giphy-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-giphy-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-giphy-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-giphy-api)

#### JavaScript module for the giphy.com API that supports promises and callbacks.

[![NPM](https://nodei.co/npm/giphy-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/giphy-api)

- [https://npmdoc.github.io/node-npmdoc-giphy-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-giphy-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-giphy-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-giphy-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-giphy-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-giphy-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Austin Kelleher, a@alk.im"
    },
    "browser": {
        "./util/http.js": "./util/http_browser.js"
    },
    "bugs": {
        "url": "https://github.com/austinkelleher/giphy-api/issues"
    },
    "dependencies": {},
    "description": "JavaScript module for the giphy.com API that supports promises and callbacks.",
    "devDependencies": {
        "browserify": "^13.0.1",
        "chai": "^3.2.0",
        "eslint-config-semistandard": "^7.0.0",
        "mocha": "^3.2.0",
        "sinon": "^1.17.3",
        "standard": "^8.6.0",
        "uglify-js": "^2.7.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "85aa0277c8954d9e8c807cffcbb43802cd2c0f60",
        "tarball": "https://registry.npmjs.org/giphy-api/-/giphy-api-1.2.5.tgz"
    },
    "gitHead": "728d1af114626ab4575a698dba9e9223496b0041",
    "homepage": "https://github.com/austinkelleher/giphy-api",
    "keywords": [
        "giphy",
        "gif",
        "api"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "austinkelleher"
        },
        {
            "name": "xdumaine"
        }
    ],
    "name": "giphy-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/austinkelleher/giphy-api.git"
    },
    "scripts": {
        "build": "./node_modules/browserify/bin/cmd.js index.js --standalone GiphyAPI > dist/giphy-api.bundle.js && ./node_modules/uglify-js/bin/uglifyjs dist/giphy-api.bundle.js --compress --output dist/giphy-api.bundle.min.js",
        "prepublish": "npm run build",
        "test": "mocha --ui bdd --reporter spec ./test"
    },
    "version": "1.2.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
