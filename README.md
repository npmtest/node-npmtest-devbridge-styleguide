# npmtest-devbridge-styleguide

#### basic test coverage for  [devbridge-styleguide (v0.4.17)](https://www.devbridge.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-devbridge-styleguide.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-devbridge-styleguide) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-devbridge-styleguide.svg)](https://travis-ci.org/npmtest/node-npmtest-devbridge-styleguide)

#### Styleguide automatization tool.

[![NPM](https://nodei.co/npm/devbridge-styleguide.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/devbridge-styleguide)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-devbridge-styleguide/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-devbridge-styleguide/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-devbridge-styleguide/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-devbridge-styleguide/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/test-report.html](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-devbridge-styleguide/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-devbridge-styleguide/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-devbridge-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-devbridge-styleguide/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-devbridge-styleguide/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gediminas Stanaitis"
    },
    "bin": {
        "styleguide": "./bin/styleguide"
    },
    "bugs": {
        "url": "https://github.com/devbridge/Styleguide/issues"
    },
    "contributors": [
        {
            "name": "Mantas Miežinas"
        }
    ],
    "dependencies": {
        "async": "1.2.1",
        "body-parser": "1.12.4",
        "colors": "1.1.2",
        "commander": "2.8.1",
        "express": "4.12.4",
        "format-json": "1.0.3",
        "jsonfile": "2.0.0",
        "lodash": "4.0.0",
        "mkdirp": "0.5.1",
        "q": "1.4.1",
        "request": "2.68.0",
        "tcp-port-used": "0.1.2"
    },
    "description": "Styleguide automatization tool.",
    "devDependencies": {
        "gulp": "^3.9.1",
        "gulp-autoprefixer": "^3.1.0",
        "gulp-sass": "^2.3.2",
        "gulp-sassvg": "^1.4.2",
        "morgan": "1.5.1",
        "node-bourbon": "^4.2.8",
        "snyk": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a8efce3309b8c4e9e88efa00589d7dcd73d952c4",
        "tarball": "https://registry.npmjs.org/devbridge-styleguide/-/devbridge-styleguide-0.4.17.tgz"
    },
    "gitHead": "427a5b857fd42f94a4389e8bbca35b926a1d3f71",
    "homepage": "https://www.devbridge.com/",
    "keywords": [
        "styleguide",
        "webstyleguide",
        "gulp",
        "sass",
        "snippet",
        "snippets",
        "colors",
        "typography",
        "scrape",
        "crawl",
        "generate",
        "styleguide-generator",
        "frontend",
        "front-end",
        "automated",
        "automatization",
        "tool"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "devbproto"
        },
        {
            "name": "miezis"
        }
    ],
    "name": "devbridge-styleguide",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/devbridge/Styleguide.git"
    },
    "scripts": {
        "test": "snyk test"
    },
    "version": "0.4.17"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
