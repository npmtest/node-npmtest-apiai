# npmtest-apiai

#### basic test coverage for  [apiai (v4.0.2)](https://github.com/api-ai/api-ai-node-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-apiai.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apiai) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apiai.svg)](https://travis-ci.org/npmtest/node-npmtest-apiai)

#### Node.js SDK for api.ai

[![NPM](https://nodei.co/npm/apiai.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apiai)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apiai/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apiai/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apiai/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apiai/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apiai/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-apiai/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-apiai/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apiai/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apiai/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apiai/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apiai/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apiai/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apiai/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apiai/build/test-report.html](https://npmtest.github.io/node-npmtest-apiai/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apiai/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apiai/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apiai/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apiai/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dmitriy Kuragin"
    },
    "bugs": {
        "url": "https://github.com/api-ai/api-ai-node-js/issues"
    },
    "dependencies": {},
    "description": "Node.js SDK for api.ai",
    "devDependencies": {
        "@types/node": "^7.0.5",
        "nodemon": "^1.11.0",
        "ts-node": "^2.1.0",
        "typescript": "^2.1.6",
        "typing": "^0.1.9",
        "typings": "^2.0.0"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "9a4d6921877e43cee4719eb73609da1d520ac857",
        "tarball": "https://registry.npmjs.org/apiai/-/apiai-4.0.2.tgz"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "module/"
    ],
    "gitHead": "a1824b0a0d315037807fdc7c5c8e304d43e3d5b4",
    "homepage": "https://github.com/api-ai/api-ai-node-js#readme",
    "keywords": [
        "apiai",
        "NLU",
        "natural",
        "language",
        "understanding"
    ],
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "sstepashka"
        }
    ],
    "name": "apiai",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/api-ai/apiai-nodejs-client.git"
    },
    "scripts": {
        "build:live": "NODE_ENV=development nodemon --exec ./node_modules/.bin/ts-node -- ./typescript_examples/text_request.ts"
    },
    "types": "index.d.ts",
    "version": "4.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
