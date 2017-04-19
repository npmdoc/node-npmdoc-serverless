# npmdoc-serverless

#### api documentation for  [serverless (v1.11.0)](https://github.com/serverless/serverless#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-serverless.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-serverless) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-serverless.svg)](https://travis-ci.org/npmdoc/node-npmdoc-serverless)

#### Serverless Framework - Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more

[![NPM](https://nodei.co/npm/serverless.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/serverless)

- [https://npmdoc.github.io/node-npmdoc-serverless/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-serverless/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serverless/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serverless/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-serverless/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-serverless/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "serverless.com"
    },
    "bin": {
        "serverless": "./bin/serverless",
        "slss": "./bin/serverless",
        "sls": "./bin/serverless"
    },
    "bugs": {
        "url": "https://github.com/serverless/serverless/issues"
    },
    "dependencies": {
        "archiver": "^1.1.0",
        "async": "^1.5.2",
        "aws-sdk": "^2.7.13",
        "bluebird": "^3.4.0",
        "chalk": "^1.1.1",
        "download": "^5.0.2",
        "filesize": "^3.3.0",
        "fs-extra": "^0.26.7",
        "get-stdin": "^5.0.1",
        "globby": "^6.1.0",
        "https-proxy-agent": "^1.0.0",
        "js-yaml": "^3.6.1",
        "json-refs": "^2.1.5",
        "lodash": "^4.13.1",
        "minimist": "^1.2.0",
        "moment": "^2.13.0",
        "node-fetch": "^1.5.3",
        "replaceall": "^0.1.6",
        "resolve-from": "^2.0.0",
        "semver": "^5.0.3",
        "semver-regex": "^1.0.0",
        "shelljs": "^0.6.0",
        "traverse": "^0.6.6",
        "uuid": "^2.0.2"
    },
    "description": "Serverless Framework - Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.12.0",
        "eslint": "^3.3.1",
        "eslint-config-airbnb": "^10.0.1",
        "eslint-config-airbnb-base": "^5.0.2",
        "eslint-plugin-import": "^1.13.0",
        "eslint-plugin-jsx-a11y": "^2.1.0",
        "eslint-plugin-react": "^6.1.1",
        "istanbul": "^0.4.4",
        "jest-cli": "^18.0.0",
        "jszip": "^3.1.2",
        "markdown-magic": "0.1.0",
        "mocha": "^3.0.2",
        "mocha-lcov-reporter": "^1.2.0",
        "mock-require": "^1.3.0",
        "proxyquire": "^1.7.10",
        "sinon": "^1.17.5",
        "sinon-bluebird": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bb87e11b334ded5249a93b6827704daa885d280c",
        "tarball": "https://registry.npmjs.org/serverless/-/serverless-1.11.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "files": [
        "bin",
        "lib",
        "scripts/postinstall.js",
        "scripts/preuninstall.js",
        "package.json",
        "npm-shrinkwrap.json",
        "README.md",
        "LICENSE.txt",
        "CHANGELOG.md"
    ],
    "gitHead": "43edb076e92aa53414d6d652a66f1102aae351a7",
    "homepage": "https://github.com/serverless/serverless#readme",
    "jest": {
        "testRegex": "(\\.|/)(tests)\\.js$",
        "setupTestFrameworkScriptFile": "<rootDir>/tests/setupTests.js"
    },
    "keywords": [
        "serverless",
        "serverless framework",
        "serverless applications",
        "serverless modules",
        "api gateway",
        "lambda",
        "aws",
        "aws lambda",
        "amazon",
        "amazon web services",
        "azure",
        "azure functions",
        "google cloud functions",
        "apache open whisk",
        "iot",
        "internet of things",
        "serverless.com"
    ],
    "license": "MIT",
    "main": "lib/Serverless.js",
    "maintainers": [
        {
            "name": "ac360"
        },
        {
            "name": "eahefnawy"
        },
        {
            "name": "serverless-main"
        }
    ],
    "name": "serverless",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/serverless/serverless.git"
    },
    "scripts": {
        "complex-integration-test": "jest --maxWorkers=5 integration",
        "docs": "node scripts/generate-readme.js",
        "lint": "eslint . --cache",
        "postinstall": "node ./scripts/postinstall.js",
        "simple-integration-test": "jest --maxWorkers=5 simple-suite",
        "test": "istanbul cover -x '**/*.test.js' node_modules/mocha/bin/_mocha '!(node_modules)/**/*.test.js' -- --require=sinon-bluebird -R spec --recursive"
    },
    "version": "1.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
