# npmdoc-react-cookie

#### api documentation for  [react-cookie (v1.0.5)](https://github.com/thereactivestack/react-cookie#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-cookie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-cookie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-cookie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-cookie)

#### Load and save cookies within your React application

[![NPM](https://nodei.co/npm/react-cookie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-cookie)

- [https://npmdoc.github.io/node-npmdoc-react-cookie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-cookie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-cookie/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-cookie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-cookie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Benoit Tremblay"
    },
    "bugs": {
        "url": "https://github.com/thereactivestack/react-cookie/issues"
    },
    "config": {
        "ghooks": {
            "pre-commit": "npm test"
        }
    },
    "dependencies": {
        "cookie": "^0.3.1",
        "is-node": "^1.0.2",
        "object-assign": "^4.1.0"
    },
    "description": "Load and save cookies within your React application",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-eslint": "^7.1.1",
        "babel-jest": "^17.0.2",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-latest": "^6.16.0",
        "babel-preset-stage-2": "^6.18.0",
        "babel-register": "^6.18.0",
        "eslint": "^3.10.2",
        "eslint-config-cyprex": "^1.1.1",
        "eslint-plugin-flowtype": "^2.30.3",
        "ghooks": "^1.3.2",
        "jest": "^17.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "234190bd55ddfea361444a89c873077ab6abf651",
        "tarball": "https://registry.npmjs.org/react-cookie/-/react-cookie-1.0.5.tgz"
    },
    "gitHead": "bb561e5a635503e5b72f30de0105b2da77137f42",
    "homepage": "https://github.com/thereactivestack/react-cookie#readme",
    "keywords": [
        "cookie",
        "cookies",
        "react",
        "reactjs",
        "jsx"
    ],
    "license": "MIT",
    "main": "build/cookie.js",
    "maintainers": [
        {
            "name": "exon"
        }
    ],
    "name": "react-cookie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thereactivestack/react-cookie.git"
    },
    "scripts": {
        "build": "babel src -d build --ignore __tests__",
        "lint": "eslint --ext .js .",
        "test": "npm run lint && jest",
        "watch": "jest --watch"
    },
    "version": "1.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
