# npmtest-elm

#### basic test coverage for  [elm (v0.18.0)](https://github.com/elm-lang/elm-platform/tree/master/installers/npm)  [![npm package](https://img.shields.io/npm/v/npmtest-elm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-elm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-elm.svg)](https://travis-ci.org/npmtest/node-npmtest-elm)

#### The Elm Platform: Binaries for the Elm programming language.

[![NPM](https://nodei.co/npm/elm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-elm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-elm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-elm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-elm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-elm/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-elm/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-elm/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-elm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-elm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-elm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-elm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-elm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-elm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-elm/build/test-report.html](https://npmtest.github.io/node-npmtest-elm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-elm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-elm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-elm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-elm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-elm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Richard Feldman",
        "url": "https://github.com/rtfeldman"
    },
    "bin": {
        "elm": "binwrappers/elm",
        "elm-make": "binwrappers/elm-make",
        "elm-package": "binwrappers/elm-package",
        "elm-reactor": "binwrappers/elm-reactor",
        "elm-repl": "binwrappers/elm-repl"
    },
    "bugs": {
        "url": "https://github.com/elm-lang/elm-platform/issues"
    },
    "dependencies": {
        "mkdirp": "0.5.1",
        "promise": "7.1.1",
        "request": "2.74.0",
        "tar": "2.2.1"
    },
    "description": "The Elm Platform: Binaries for the Elm programming language.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "919b8309cd939dfe2ff9d252d961b6c89509b970",
        "tarball": "https://registry.npmjs.org/elm/-/elm-0.18.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "install.js",
        "platform.js",
        "binaries.json",
        "binwrap.js",
        "binwrappers"
    ],
    "homepage": "https://github.com/elm-lang/elm-platform/tree/master/installers/npm",
    "keywords": [
        "bin",
        "binary",
        "binaries",
        "elm",
        "elm-make",
        "elm-package",
        "elm-platform",
        "elm-reactor",
        "elm-repl",
        "platform"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "evancz"
        },
        {
            "name": "rtfeldman"
        }
    ],
    "name": "elm",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/elm-lang/elm-platform.git"
    },
    "scripts": {
        "install": "node install.js"
    },
    "version": "0.18.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
