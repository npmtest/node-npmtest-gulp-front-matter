# npmtest-gulp-front-matter

#### basic test coverage for  [gulp-front-matter (v1.3.0)](https://github.com/lmtm/gulp-front-matter#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-front-matter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-front-matter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-front-matter.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-front-matter)

#### Extract front-matter header from files

[![NPM](https://nodei.co/npm/gulp-front-matter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-front-matter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-front-matter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-front-matter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-front-matter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-front-matter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-front-matter/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-front-matter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-front-matter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-front-matter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-front-matter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-front-matter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Chambrier",
        "url": "http://naholyr.fr/"
    },
    "bugs": {
        "url": "https://github.com/lmtm/gulp-front-matter/issues"
    },
    "contributors": [
        {
            "name": "Shinnosuke Watanabe",
            "url": "https://github.com/shinnn"
        }
    ],
    "dependencies": {
        "front-matter": "^2.0.0",
        "gulp-util": "^3.0.6",
        "object-path": "^0.9.2",
        "readable-stream": "^2.0.3",
        "tryit": "^1.0.1",
        "vinyl-bufferstream": "^1.0.1"
    },
    "description": "Extract front-matter header from files",
    "devDependencies": {
        "@shinnn/eslint-config-node-legacy": "^1.0.0",
        "eslint": "^1.7.3",
        "from2-string": "^1.1.0",
        "istanbul": "^0.4.0",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.2",
        "vinyl": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5ee466fbfafb33420bcd5e0267bb6819444ab06d",
        "tarball": "https://registry.npmjs.org/gulp-front-matter/-/gulp-front-matter-1.3.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "132c2edee0385095bcbb2cfe4843565562356526",
    "homepage": "https://github.com/lmtm/gulp-front-matter#readme",
    "keywords": [
        "gulpplugin",
        "yml",
        "yaml",
        "parse",
        "data",
        "property",
        "extract",
        "attribute",
        "attributes",
        "frontmatter",
        "front-matter",
        "meta",
        "metadata",
        "meta-data"
    ],
    "license": "BSD-2-Clause",
    "maintainers": [
        {
            "name": "shinnn"
        }
    ],
    "name": "gulp-front-matter",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lmtm/gulp-front-matter.git"
    },
    "scripts": {
        "coverage": "istanbul cover test.js",
        "coveralls": "${npm_package_scripts_coverage} && istanbul-coveralls",
        "pretest": "eslint --config @shinnn/node-legacy index.js test.js",
        "test": "node test.js | tap-spec"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
