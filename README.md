# npmtest-git-changelog

#### basic test coverage for  [git-changelog (v1.1.2)](https://github.com/rafinskipg/git-changelog)  [![npm package](https://img.shields.io/npm/v/npmtest-git-changelog.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-git-changelog) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-git-changelog.svg)](https://travis-ci.org/npmtest/node-npmtest-git-changelog)

#### A git changelog tool

[![NPM](https://nodei.co/npm/git-changelog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/git-changelog)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-git-changelog/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-git-changelog/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-git-changelog/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-git-changelog/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-git-changelog/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-git-changelog/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-git-changelog/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-git-changelog/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-git-changelog/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-git-changelog/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-git-changelog/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-git-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-git-changelog/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-git-changelog/build/test-report.html](https://npmtest.github.io/node-npmtest-git-changelog/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-git-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-git-changelog/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-git-changelog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-git-changelog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-git-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-git-changelog/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-git-changelog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-git-changelog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "rafinskipg"
    },
    "bin": {
        "git-changelog": "tasks/command.js"
    },
    "bugs": {
        "url": "https://github.com/rafinskipg/git-changelog/issues"
    },
    "dependencies": {
        "colors": "^1.1.0",
        "commander": "^2.8.0",
        "debug": "^2.1.3",
        "fs-extra": "^0.18.4",
        "lodash": "^3.7.0",
        "q": "^1.2.0"
    },
    "description": "A git changelog tool",
    "devDependencies": {
        "chai": "^2.2.0",
        "chai-as-promised": "^5.0.0",
        "grunt": "^1.0.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-mocha-test": "^0.12.1",
        "istanbul": "^0.3.13",
        "mocha": "^2.2.4",
        "sinon": "^1.14.1",
        "sinon-chai": "^2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bb07dce3fa98956abb477f2a7fd5cd0ddfe0ca38",
        "tarball": "https://registry.npmjs.org/git-changelog/-/git-changelog-1.1.2.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "49a00ad3e8892f5f07775f5d54f84338e0c98759",
    "homepage": "https://github.com/rafinskipg/git-changelog",
    "keywords": [
        "gruntplugin, git, git-changelog, angularjs, angular, commit, log"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/rafinskipg/git-changelog/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "rafinskipg"
        }
    ],
    "name": "git-changelog",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git://github.com/rafinskipg/git-changelog.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/.bin/_mocha -- -R dot",
        "post-test": "grunt",
        "pre-test": "grunt",
        "preversion": "npm test",
        "test": "mocha -R spec test/**/*.spec.js"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
