# npmdoc-vue-loader

#### basic api documentation for  [vue-loader (v12.0.2)](https://github.com/vuejs/vue-loader)  [![npm package](https://img.shields.io/npm/v/npmdoc-vue-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-vue-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-vue-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-vue-loader)

#### Vue single-file component loader for Webpack

[![NPM](https://nodei.co/npm/vue-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-loader)

- [https://npmdoc.github.io/node-npmdoc-vue-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-vue-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-vue-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan You"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vue-loader/issues"
    },
    "dependencies": {
        "consolidate": "^0.14.0",
        "hash-sum": "^1.0.2",
        "js-beautify": "^1.6.3",
        "loader-utils": "^1.1.0",
        "lru-cache": "^4.0.1",
        "postcss": "^5.0.21",
        "postcss-load-config": "^1.1.0",
        "postcss-selector-parser": "^2.0.0",
        "resolve": "^1.3.3",
        "source-map": "^0.5.6",
        "vue-hot-reload-api": "^2.1.0",
        "vue-style-loader": "^3.0.0",
        "vue-template-es2015-compiler": "^1.2.2"
    },
    "description": "Vue single-file component loader for Webpack",
    "devDependencies": {
        "babel-core": "^6.8.0",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "chai": "^3.0.0",
        "coffee-loader": "^0.7.2",
        "coffee-script": "^1.10.0",
        "css-loader": "^0.26.0",
        "eslint": "^3.14.1",
        "eslint-config-vue": "^2.0.2",
        "eslint-plugin-vue": "^2.0.0",
        "expose-loader": "^0.7.1",
        "extract-text-webpack-plugin": "^2.0.0-rc.0",
        "file-loader": "^0.10.0",
        "inject-loader": "^2.0.0",
        "js-yaml": "^3.8.2",
        "jsdom": "^9.2.1",
        "marked": "^0.3.6",
        "memory-fs": "^0.4.1",
        "mkdirp": "^0.5.1",
        "mocha": "^3.2.0",
        "node-libs-browser": "^2.0.0",
        "normalize-newline": "^3.0.0",
        "null-loader": "^0.1.1",
        "pug": "^2.0.0-beta6",
        "raw-loader": "^0.5.1",
        "skeleton-loader": "0.0.5",
        "stylus": "^0.54.5",
        "stylus-loader": "^2.0.0",
        "sugarss": "^0.2.0",
        "url-loader": "^0.5.7",
        "vue": "^2.3.0-beta.1",
        "vue-server-renderer": "^2.3.0-beta.1",
        "vue-template-compiler": "^2.3.0-beta.1",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f539036b1e0e9516b474a8fd1b5f533145248406",
        "tarball": "https://registry.npmjs.org/vue-loader/-/vue-loader-12.0.2.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "08491c9e3802dab47f07a67e20dc3ef87e48ecf8",
    "homepage": "https://github.com/vuejs/vue-loader",
    "keywords": [
        "vue",
        "webpack",
        "loader"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "yyx990803"
        }
    ],
    "name": "vue-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "css-loader": "*",
        "vue-template-compiler": "^2.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vue-loader.git"
    },
    "scripts": {
        "docs": "cd docs && gitbook serve",
        "docs:deploy": "bash ./docs/deploy.sh",
        "lint": "eslint lib",
        "test": "eslint lib && mocha --slow 5000 --timeout 10000"
    },
    "version": "12.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
