# npmtest-express-hbs

#### basic test coverage for  [express-hbs (v1.0.4)](https://github.com/barc/express-hbs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-hbs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-hbs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-hbs.svg)](https://travis-ci.org/npmtest/node-npmtest-express-hbs)

#### Express 3 handlebars template engine complete with multiple layouts, partials and blocks.

[![NPM](https://nodei.co/npm/express-hbs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-hbs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-hbs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-hbs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-hbs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-hbs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-hbs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-hbs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-hbs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-hbs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-hbs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-hbs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-hbs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-hbs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-hbs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-hbs/build/test-report.html](https://npmtest.github.io/node-npmtest-express-hbs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-hbs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-hbs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-hbs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-hbs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-hbs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-hbs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-hbs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-hbs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mario Gutierrez"
    },
    "bugs": {
        "url": "https://github.com/barc/express-hbs/issues"
    },
    "dependencies": {
        "handlebars": "4.0.6",
        "js-beautify": "1.6.8",
        "readdirp": "2.1.0"
    },
    "description": "Express 3 handlebars template engine complete with multiple layouts, partials and blocks.",
    "devDependencies": {
        "cookie-parser": "1.4.3",
        "express": "4.14.0",
        "grunt": "1.0.1",
        "grunt-mocha-cli": "3.0.0",
        "grunt-release": "0.14.0",
        "i18n": "0.8.3",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "rewire": "2.5.2",
        "supertest": "2.0.1"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "c4480d6e8a9f8c23500d3b1a1394f17eae451786",
        "tarball": "https://registry.npmjs.org/express-hbs/-/express-hbs-1.0.4.tgz"
    },
    "gitHead": "76b997802d57e683eb4d90e6c02225e3c7b5e584",
    "homepage": "https://github.com/barc/express-hbs#readme",
    "keywords": [
        "express3",
        "express",
        "handlebars",
        "layout",
        "partials"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mgutz"
        },
        {
            "name": "erisds"
        }
    ],
    "name": "express-hbs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/barc/express-hbs.git"
    },
    "scripts": {
        "coverage": "NODE_ENV=testing ./node_modules/.bin/istanbul cover --dir test/coverage -x 'example/**' ./node_modules/.bin/_mocha",
        "test": "grunt"
    },
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
