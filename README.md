# npmdoc-ml-sentiment

#### basic api documentation for  [ml-sentiment (v2.0.7)](https://github.com/syzer/sentiment-analyser#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ml-sentiment.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ml-sentiment) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ml-sentiment.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ml-sentiment)

#### Machine learner sentiment classifier, with ability to negate words, with english and german

[![NPM](https://nodei.co/npm/ml-sentiment.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ml-sentiment)

- [https://npmdoc.github.io/node-npmdoc-ml-sentiment/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ml-sentiment/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ml-sentiment/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ml-sentiment/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ml-sentiment/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ml-sentiment/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/syzer/sentiment-analyser/issues"
    },
    "dependencies": {
        "lodash-fp": "^0.10.4"
    },
    "description": "Machine learner sentiment classifier, with ability to negate words, with english and german",
    "devDependencies": {
        "argg": "0.0.2",
        "codecov.io": "^0.1.6",
        "istanbul": "^0.4.0",
        "tap": "^8.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f8b59a85ad2c4107c332d0afb5dea8927b411e81",
        "tarball": "https://registry.npmjs.org/ml-sentiment/-/ml-sentiment-2.0.7.tgz"
    },
    "gitHead": "7bd7894ebef61b3b524a3c367d562bc6595ab078",
    "homepage": "https://github.com/syzer/sentiment-analyser#readme",
    "keywords": [
        "machine learning",
        "sentiment",
        "analyser",
        "nlp",
        "ml",
        "natural language processing"
    ],
    "license": "ISC",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "syzer"
        }
    ],
    "name": "ml-sentiment",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/syzer/sentiment-analyser.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/argg test/*.js && cat ./coverage/lcov.info | ./node_modules/.bin/codecov",
        "coverage-local": "istanbul cover node_modules/argg test/*.js",
        "test": "tap test/*.js"
    },
    "version": "2.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
