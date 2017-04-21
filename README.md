# npmdoc-regexgen

#### api documentation for  [regexgen (v1.2.3)](https://github.com/devongovett/regexgen#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-regexgen.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-regexgen) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-regexgen.svg)](https://travis-ci.org/npmdoc/node-npmdoc-regexgen)

#### Generate regular expressions that match a set of strings

[![NPM](https://nodei.co/npm/regexgen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/regexgen)

- [https://npmdoc.github.io/node-npmdoc-regexgen/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-regexgen/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-regexgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-regexgen/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-regexgen/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-regexgen/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "regexgen",
    "version": "1.2.3",
    "description": "Generate regular expressions that match a set of strings",
    "main": "index.js",
    "bin": {
        "regexgen": "bin/cli.js"
    },
    "dependencies": {
        "jsesc": "^2.3.0",
        "regenerate": "^1.3.2"
    },
    "devDependencies": {
        "mocha": "^3.2.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "engines": {
        "node": ">= 6"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/devongovett/regexgen.git"
    },
    "keywords": [
        "regex",
        "trie",
        "regular",
        "expression"
    ],
    "author": "Devon Govett <devongovett@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/devongovett/regexgen/issues"
    },
    "homepage": "https://github.com/devongovett/regexgen#readme",
    "runkitExample": "const regexgen = require('regexgen');\n\nregexgen(['foobar', 'foobaz', 'foozap', 'fooza']);"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
