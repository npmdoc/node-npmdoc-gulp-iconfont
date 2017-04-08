# api documentation for  [gulp-iconfont (v8.0.1)](https://github.com/nfroidure/gulp-iconfont)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-iconfont.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-iconfont) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-iconfont.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-iconfont)
#### Create icon fonts from several SVG icons

[![NPM](https://nodei.co/npm/gulp-iconfont.png?downloads=true)](https://www.npmjs.com/package/gulp-iconfont)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-iconfont/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-iconfont%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-iconfont/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-iconfont/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-iconfont/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Froidure",
        "url": "http://www.insertafter.com/blog.html"
    },
    "bugs": {
        "url": "https://github.com/nfroidure/gulp-iconfont/issues"
    },
    "dependencies": {
        "gulp-cond": "^1.0.0",
        "gulp-spawn": "^0.3.0",
        "gulp-svg2ttf": "^2.0.0",
        "gulp-svgicons2svgfont": "^3.0.1",
        "gulp-ttf2eot": "^1.1.1",
        "gulp-ttf2woff": "^1.1.0",
        "gulp-ttf2woff2": "^2.0.2",
        "gulp-util": "^3.0.7",
        "plexer": "^1.0.1",
        "streamfilter": "^1.0.5"
    },
    "description": "Create icon fonts from several SVG icons",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "eslint": "^1.10.1",
        "eslint-config-simplifield": "^1.2.2",
        "gulp": "^3.9.1",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.5",
        "mocha-lcov-reporter": "^1.0.0",
        "neatequal": "^1.0.0",
        "streamtest": "^1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "bc32aa6e3ea5ca389fbb014ba8d2c08f0c3c0763",
        "tarball": "https://registry.npmjs.org/gulp-iconfont/-/gulp-iconfont-8.0.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "e7d32eb141f6106a04d03a21ddfc66259983f8f0",
    "homepage": "https://github.com/nfroidure/gulp-iconfont",
    "keywords": [
        "gulpplugin",
        "gulp",
        "icon",
        "font"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "nfroidure",
            "email": "nfroidure@elitwork.com"
        }
    ],
    "name": "gulp-iconfont",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nfroidure/gulp-iconfont.git"
    },
    "scripts": {
        "cli": "env NPM_RUN_CLI=1",
        "cover": "istanbul cover --report html _mocha -- tests/*.mocha.js -R spec -t 5000",
        "coveralls": "istanbul cover _mocha --report lcovonly -- tests/*.mocha.js -R spec -t 5000 && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "generate-fixtures": "./tests/generate-fixtures.sh",
        "lint": "eslint src/*.js tests/*.js",
        "preversion": "npm run lint && npm test",
        "test": "mocha tests/*.mocha.js"
    },
    "version": "8.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-iconfont](#apidoc.module.gulp-iconfont)



# <a name="apidoc.module.gulp-iconfont"></a>[module gulp-iconfont](#apidoc.module.gulp-iconfont)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
