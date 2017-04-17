# api documentation for  [njwt (v0.4.0)](https://github.com/jwtk/njwt)  [![npm package](https://img.shields.io/npm/v/npmdoc-njwt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-njwt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-njwt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-njwt)
#### JWT Library for Node.js

[![NPM](https://nodei.co/npm/njwt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/njwt)

- [https://npmdoc.github.io/node-npmdoc-njwt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-njwt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-njwt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-njwt/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-njwt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-njwt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stormpath, Inc."
    },
    "bugs": {
        "url": "https://github.com/jwtk/njwt/issues"
    },
    "dependencies": {
        "ecdsa-sig-formatter": "^1.0.5",
        "uuid": "^2.0.1"
    },
    "description": "JWT Library for Node.js",
    "devDependencies": {
        "chai": "^2.2.0",
        "coveralls": "^2.11.15",
        "istanbul": "^0.4.5",
        "jsonwebtoken": "^5.0.2",
        "jwt-simple": "^0.3.0",
        "mocha": "^3.2.0",
        "secure-random": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7324ed9d76a9d54b5e265cb7b6a3c55f146fd3c7",
        "tarball": "https://registry.npmjs.org/njwt/-/njwt-0.4.0.tgz"
    },
    "gitHead": "3bc7df1fa56fa139d1070e288152a5fd3d41c44a",
    "homepage": "https://github.com/jwtk/njwt",
    "keywords": [
        "jwt"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "robertjd"
        },
        {
            "name": "lhazlewood"
        }
    ],
    "name": "njwt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jwtk/njwt.git"
    },
    "scripts": {
        "test": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly test/ -- -R spec --no-timeouts; cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js; rm -rf ./coverage",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --timeout=5000 --reporter dot --check-leaks test/",
        "test-debug": "mocha --timeout=5000 --debug --reporter dot --check-leaks -w ./*.js test/ ",
        "test-watch": "mocha --timeout=5000 --reporter dot --check-leaks -w ./*.js test/ "
    },
    "version": "0.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
