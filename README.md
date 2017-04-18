# npmtest-gulp.spritesmith-multi

#### test coverage for  [gulp.spritesmith-multi (v3.1.0)](https://github.com/reducejs/gulp.spritesmith-multi#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp.spritesmith-multi.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp.spritesmith-multi) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp.spritesmith-multi.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp.spritesmith-multi)

#### A wrapper for gulp.spritesmith to generate multiple sprites and stylesheets

[![NPM](https://nodei.co/npm/gulp.spritesmith-multi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp.spritesmith-multi)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp.spritesmith-multi/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp.spritesmith-multi/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp.spritesmith-multi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp.spritesmith-multi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp.spritesmith-multi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp.spritesmith-multi/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp.spritesmith-multi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "zoubin"
    },
    "bugs": {
        "url": "https://github.com/reducejs/gulp.spritesmith-multi/issues"
    },
    "dependencies": {
        "gulp.spritesmith": "^6.0.0",
        "handlebars": "^4.0.5",
        "merge-stream": "^1.0.0",
        "mixy": "^1.0.0",
        "through2": "^2.0.0"
    },
    "description": "A wrapper for gulp.spritesmith to generate multiple sprites and stylesheets",
    "devDependencies": {
        "callback-sequence": "^3.0.0",
        "del": "^2.0.0",
        "eslint": "^2.1.0",
        "gulp": "^3.9.0",
        "gulp-csso": "^1.0.1",
        "gulp-imagemin": "^2.4.0",
        "tap": "^5.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8b54f89fa0879e30c344faa050a36f4ccd35cc13",
        "tarball": "https://registry.npmjs.org/gulp.spritesmith-multi/-/gulp.spritesmith-multi-3.1.0.tgz"
    },
    "gitHead": "d9d3aef2a191305ce2319d015f88fdfb4a96f20a",
    "homepage": "https://github.com/reducejs/gulp.spritesmith-multi#readme",
    "keywords": [
        "spritesmith",
        "gulp",
        "sprite",
        "css"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "zoubin"
        }
    ],
    "name": "gulp.spritesmith-multi",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reducejs/gulp.spritesmith-multi.git"
    },
    "scripts": {
        "cov": "tap --cov test/*.js",
        "coveralls": "COVERALLS_REPO_TOKEN=BJcooCig6VD9s8fRm2YPFv6mmvrPUhXoh npm run cov",
        "lint": "eslint *.js 'lib/**/*.js' test/*.js bin/*.js",
        "test": "npm run lint && tap test/*.js"
    },
    "version": "3.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
