# npmtest-typedoc

#### basic test coverage for  [typedoc (v0.5.10)](http://typedoc.org)  [![npm package](https://img.shields.io/npm/v/npmtest-typedoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-typedoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-typedoc.svg)](https://travis-ci.org/npmtest/node-npmtest-typedoc)

#### Create api documentations for typescript projects.

[![NPM](https://nodei.co/npm/typedoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/typedoc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-typedoc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-typedoc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-typedoc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-typedoc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-typedoc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-typedoc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-typedoc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-typedoc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-typedoc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-typedoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-typedoc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-typedoc/build/test-report.html](https://npmtest.github.io/node-npmtest-typedoc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-typedoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-typedoc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-typedoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-typedoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typedoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typedoc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-typedoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-typedoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian Lenz",
        "url": "http://www.sebastian-lenz.de/"
    },
    "bin": {
        "typedoc": "bin/typedoc"
    },
    "bugs": {
        "url": "https://github.com/TypeStrong/TypeDoc/issues"
    },
    "dependencies": {
        "@types/fs-extra": "0.0.33",
        "@types/handlebars": "^4.0.31",
        "@types/highlight.js": "^9.1.8",
        "@types/lodash": "^4.14.37",
        "@types/marked": "0.0.28",
        "@types/minimatch": "^2.0.29",
        "@types/shelljs": "^0.3.32",
        "fs-extra": "^2.0.0",
        "handlebars": "4.0.5",
        "highlight.js": "^9.0.0",
        "lodash": "^4.13.1",
        "marked": "^0.3.5",
        "minimatch": "^3.0.0",
        "progress": "^1.1.8",
        "shelljs": "^0.7.0",
        "typedoc-default-themes": "^0.4.2",
        "typescript": "2.2.2"
    },
    "description": "Create api documentations for typescript projects.",
    "devDependencies": {
        "@types/mocha": "^2.2.39",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-mocha-istanbul": "^5.0.1",
        "grunt-string-replace": "^1.2.0",
        "grunt-ts": "^5.5.1",
        "grunt-tslint": "^4.0.1",
        "istanbul": "^0.4.1",
        "mocha": "^3.0.2",
        "tslint": "^4.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4bd60c53c423811931fc519ffb36e58338824335",
        "tarball": "https://registry.npmjs.org/typedoc/-/typedoc-0.5.10.tgz"
    },
    "engines": {
        "node": ">= 4.2.0"
    },
    "files": [
        "bin",
        "dist",
        "!dist/test",
        "tasks",
        "LICENSE"
    ],
    "gitHead": "f70291e74e981c76782033cbdd38764361c770bd",
    "homepage": "http://typedoc.org",
    "keywords": [
        "typescript",
        "documentation",
        "generator",
        "gruntplugin"
    ],
    "license": "Apache-2.0",
    "licenses": [
        {
            "type": "Apache-2.0",
            "url": "https://github.com/TypeStrong/TypeDoc/blob/master/LICENSE"
        }
    ],
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        },
        {
            "name": "sebastian-lenz"
        }
    ],
    "name": "typedoc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/TypeStrong/TypeDoc.git"
    },
    "scripts": {
        "build": "grunt build_and_test",
        "prepublish": "npm run build",
        "test": "mocha -t 4000 dist/test"
    },
    "typings": "dist/index.d.ts",
    "version": "0.5.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
