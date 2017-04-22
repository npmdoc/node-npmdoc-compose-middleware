# npmdoc-compose-middleware

#### api documentation for  [compose-middleware (v2.2.0)](https://github.com/blakeembrey/compose-middleware)  [![npm package](https://img.shields.io/npm/v/npmdoc-compose-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-compose-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-compose-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-compose-middleware)

#### Compose an array of middleware into a single function for use in Express, Connect, router, etc.

[![NPM](https://nodei.co/npm/compose-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/compose-middleware)

- [https://npmdoc.github.io/node-npmdoc-compose-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-compose-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-compose-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-compose-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-compose-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-compose-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
        "url": "http://blakeembrey.me"
    },
    "bugs": {
        "url": "https://github.com/blakeembrey/compose-middleware/issues"
    },
    "dependencies": {
        "array-flatten": "^2.1.0"
    },
    "description": "Compose an array of middleware into a single function for use in Express, Connect, router, etc.",
    "devDependencies": {
        "chai": "^3.2.0",
        "istanbul": "^0.4.4",
        "mocha": "^2.2.5",
        "tslint": "^3.11.0",
        "tslint-config-standard": "^1.2.2",
        "typescript": "^1.5.3",
        "typings": "^1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6e830b1c5c168d3bf1fec62e3a964c2dd361cec3",
        "tarball": "https://registry.npmjs.org/compose-middleware/-/compose-middleware-2.2.0.tgz"
    },
    "files": [
        "lib/",
        "LICENSE"
    ],
    "gitHead": "d1497bf1362310b7ea575dbe23e8a1a0ec8deaa2",
    "homepage": "https://github.com/blakeembrey/compose-middleware",
    "keywords": [
        "middleware",
        "express",
        "compose",
        "flatten",
        "function"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        }
    ],
    "name": "compose-middleware",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/blakeembrey/compose-middleware.git"
    },
    "scripts": {
        "build": "rm -rf lib && npm run build-ts",
        "build-ts": "tsc",
        "lint": "tslint \"src/**/*.ts\"",
        "prepublish": "typings install && npm run build",
        "test": "npm run build && npm run lint && npm run test-cov",
        "test-cov": "istanbul cover -x *.spec.js node_modules/mocha/bin/_mocha -- lib/**/*.spec.js -R spec --bail",
        "test-spec": "mocha lib/**/*.spec.js -R spec --bail"
    },
    "typings": "lib/index.d.ts",
    "version": "2.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
