# npmdoc-jhipster-uml

#### api documentation for  [jhipster-uml (v2.0.3)](https://github.com/jhipster/jhipster-uml)  [![npm package](https://img.shields.io/npm/v/npmdoc-jhipster-uml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jhipster-uml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jhipster-uml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jhipster-uml)

#### UML support for JHipster via XMI files

[![NPM](https://nodei.co/npm/jhipster-uml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jhipster-uml)

- [https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jhipster-uml",
    "version": "2.0.3",
    "description": "UML support for JHipster via XMI files",
    "bin": {
        "jhipster-uml": "./jhipster-uml.js"
    },
    "keywords": [
        "generator-jhipster",
        "UML",
        "XMI",
        "JSON"
    ],
    "homepage": "https://github.com/jhipster/jhipster-uml",
    "bugs": "https://github.com/jhipster/jhipster-uml/issues",
    "author": {
        "name": "Mathieu Abou-Aichi",
        "url": "https://github.com/MathieuAA"
    },
    "main": "module/index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/jhipster/jhipster-uml.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha test",
        "coverage": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha test; ./node_modules/istanbul/lib/cli.js check-coverage"
    },
    "dependencies": {
        "chalk": "1.1.3",
        "deasync": "0.1.9",
        "inquirer": "2.0.0",
        "jhipster-core": "1.2.6",
        "lodash": "4.17.4",
        "xml2js": "0.4.17",
        "yargs": "6.6.0"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "mocha-clean": "1.0.0"
    },
    "peerDependencies": {},
    "engines": {
        "node": ">=4.0.0",
        "npm": ">=2.14.2"
    },
    "license": "Apache-2.0",
    "licenses": [
        {
            "type": "Apache 2.0"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
