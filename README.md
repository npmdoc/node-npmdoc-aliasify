# api documentation for  [aliasify (v2.1.0)](https://github.com/benbria/aliasify#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-aliasify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aliasify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aliasify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aliasify)
#### Rewrite require calls in browserify modules.

[![NPM](https://nodei.co/npm/aliasify.png?downloads=true)](https://www.npmjs.com/package/aliasify)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aliasify/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-aliasify_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aliasify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aliasify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aliasify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Walton",
        "url": "https://github.com/jwalton"
    },
    "bugs": {
        "url": "https://github.com/benbria/aliasify/issues"
    },
    "contributors": [
        {
            "name": "Jason Walton",
            "email": "dev@lucid.thedreaming.org",
            "url": "https://github.com/jwalton"
        }
    ],
    "dependencies": {
        "browserify-transform-tools": "~1.7.0"
    },
    "description": "Rewrite require calls in browserify modules.",
    "devDependencies": {
        "coffee-coverage": "^0.7.0",
        "coffee-script": "^1.8.0",
        "coveralls": "^2.11.6",
        "es6-promise": "^3.0.2",
        "istanbul": "^0.4.1",
        "mocha": "^2.1.0",
        "promise-breaker": "^3.0.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "7c30825b9450b9e6185ba27533eaf6e2067d4b42",
        "tarball": "https://registry.npmjs.org/aliasify/-/aliasify-2.1.0.tgz"
    },
    "gitHead": "6dba2aa9fccc0336186353b8cf1e06158e611999",
    "homepage": "https://github.com/benbria/aliasify#readme",
    "keywords": [
        "browserify",
        "alias"
    ],
    "license": "MIT",
    "main": "./lib/aliasify.js",
    "maintainers": [
        {
            "name": "jwalton",
            "email": "npm@lucid.thedreaming.org"
        },
        {
            "name": "kreisys",
            "email": "shaybergmann@gmail.com"
        },
        {
            "name": "metelyk",
            "email": "dbronnykova@benbria.ca"
        }
    ],
    "name": "aliasify",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/benbria/aliasify.git"
    },
    "scripts": {
        "build": "coffee -c -o lib src",
        "prepublish": "coffee -c -o lib src && mocha test",
        "test": "mocha && istanbul report text-summary lcov"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module aliasify](#apidoc.module.aliasify)
1.  [function <span class="apidocSignatureSpan">aliasify.</span>configure (config)](#apidoc.element.aliasify.configure)



# <a name="apidoc.module.aliasify"></a>[module aliasify](#apidoc.module.aliasify)

#### <a name="apidoc.element.aliasify.configure"></a>[function <span class="apidocSignatureSpan">aliasify.</span>configure (config)](#apidoc.element.aliasify.configure)
- description and source-code
```javascript
configure = function (config) {
  return function(file) {
    return module.exports(file, config);
  };
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
