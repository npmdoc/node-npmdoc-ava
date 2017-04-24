# npmdoc-ava

#### api documentation for  [ava (v0.19.1)](https://ava.li)  [![npm package](https://img.shields.io/npm/v/npmdoc-ava.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ava) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ava.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ava)

#### Futuristic test runner 🚀

[![NPM](https://nodei.co/npm/ava.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ava)

- [https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ava",
    "version": "0.19.1",
    "description": "Futuristic test runner 🚀",
    "license": "MIT",
    "repository": "avajs/ava",
    "homepage": "https://ava.li",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "maintainers": [
        {
            "name": "Vadim Demedes",
            "url": "github.com/vadimdemedes"
        },
        {
            "name": "James Talmage",
            "url": "github.com/jamestalmage"
        },
        {
            "name": "Mark Wubben",
            "url": "novemberborn.net"
        },
        {
            "name": "Juan Soto",
            "url": "juansoto.me"
        },
        {
            "name": "Jeroen Engels",
            "url": "github.com/jfmengels"
        }
    ],
    "bin": "cli.js",
    "typings": "types/generated.d.ts",
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && flow check test/flow-types && tsc -p test/ts-types && nyc tap --no-cov --timeout=150 --jobs=4 test/*.js test/reporters/*.js",
        "test-win": "tap --no-cov --reporter=classic --timeout=150 --jobs=4 test/*.js test/reporters/*.js",
        "visual": "node test/visual/run-visual-tests.js",
        "prepublish": "npm run make-ts",
        "make-ts": "node types/make.js"
    },
    "files": [
        "lib",
        "*.js",
        "*.js.flow",
        "types/generated.d.ts"
    ],
    "keywords": [
        "test",
        "runner",
        "ava",
        "concurrent",
        "parallel",
        "fast",
        "tape",
        "tap",
        "jest",
        "mocha",
        "qunit",
        "jasmine",
        "testing",
        "tdd",
        "cli-app",
        "cli",
        "assert",
        "assertion",
        "futuristic",
        "promise",
        "promises",
        "async",
        "function",
        "await",
        "generator",
        "generators",
        "yield",
        "observable",
        "observables"
    ],
    "dependencies": {
        "@ava/babel-preset-stage-4": "^1.0.0",
        "@ava/babel-preset-transform-test-files": "^3.0.0",
        "@ava/pretty-format": "^1.1.0",
        "arr-flatten": "^1.0.1",
        "array-union": "^1.0.1",
        "array-uniq": "^1.0.2",
        "arrify": "^1.0.0",
        "auto-bind": "^1.1.0",
        "ava-init": "^0.2.0",
        "babel-code-frame": "^6.16.0",
        "babel-core": "^6.17.0",
        "bluebird": "^3.0.0",
        "caching-transform": "^1.0.0",
        "chalk": "^1.0.0",
        "chokidar": "^1.4.2",
        "clean-stack": "^1.1.1",
        "clean-yaml-object": "^0.1.0",
        "cli-cursor": "^2.1.0",
        "cli-spinners": "^1.0.0",
        "cli-truncate": "^1.0.0",
        "co-with-promise": "^4.6.0",
        "code-excerpt": "^2.1.0",
        "common-path-prefix": "^1.0.0",
        "convert-source-map": "^1.2.0",
        "core-assert": "^0.2.0",
        "currently-unhandled": "^0.4.1",
        "debug": "^2.2.0",
        "diff": "^3.0.1",
        "diff-match-patch": "^1.0.0",
        "dot-prop": "^4.1.0",
        "empower-core": "^0.6.1",
        "equal-length": "^1.0.0",
        "figures": "^2.0.0",
        "find-cache-dir": "^0.1.1",
        "fn-name": "^2.0.0",
        "get-port": "^3.0.0",
        "globby": "^6.0.0",
        "has-flag": "^2.0.0",
        "hullabaloo-config-manager": "^1.0.0",
        "ignore-by-default": "^1.0.0",
        "indent-string": "^3.0.0",
        "is-ci": "^1.0.7",
        "is-generator-fn": "^1.0.0",
        "is-obj": "^1.0.0",
        "is-observable": "^0.2.0",
        "is-promise": "^2.1.0",
        "jest-diff": "19.0.0",
        "jest-snapshot": "19.0.2",
        "js-yaml": "^3.8.2",
        "last-line-stream": "^1.0.0",
        "lodash.debounce": "^4.0.3",
        "lodash.difference": "^4.3.0",
        "lodash.flatten": "^4.2.0",
        "lodash.isequal": "^4.5.0",
        "loud-rejection": "^1.2.0",
        "matcher": "^0.1.1",
        "md5-hex": "^2.0.0",
        "meow": "^3.7.0",
        "mkdirp": "^0.5.1",
        "ms": "^0.7.1",
        "multimatch": "^2.1.0",
        "observable-to-promise": "^0.5.0",
        "option-chain": "^0.1.0",
        "package-hash": "^2.0.0",
        "pkg-conf": "^2.0.0",
        "plur": "^2.0.0",
        "pretty-ms": "^2.0.0",
        "require-precompiled": "^0.1.0",
        "resolve-cwd": "^1.0.0",
        "slash": "^1.0.0",
        "source-map-support": "^0.4.0",
        "stack-utils": "^1.0.0",
        "strip-ansi": "^3.0.1",
        "strip-bom-buf": "^1.0.0",
        "supports-color": "^3.2.3",
        "time-require": "^0.1.2",
        "unique-temp-dir": "^1.0.0",
        "update-notifier": "^2.1.0"
    },
    "devDependencies": {
        "babel-preset-react": "^6.5.0",
        "cli-table2": "^0.2.0",
        "coveralls": "^2.11.4",
        "delay": "^1.3.0",
        "execa": "^0.6.0",
        "flow-bin": "^0.42.0",
        "get-stream": "^3.0.0",
        "git-branch": "^0.3.0",
        "has-ansi": "^2.0.0",
        "inquirer": "^3.0.5",
        "is-array-sorted": "^1.0.0",
        "lolex": "^1.4.0",
        "nyc": "^10.0.0",
        "proxyquire": "^1.7.4",
        "rimraf": "^2.5.0",
        "signal-exit": "^3.0.0",
        "sinon": "^2.0.0",
        "source-map-fixtures": "^2.1.0",
        "tap": "^10.0.0",
        "temp-write": "^3.1.0",
        "touch": "^1.0.0",
        "typescript": "^2.2.2",
        "xo": "^0.18.0",
        "zen-observable": "^0.5.1"
    },
    "xo": {
        "esnext": true,
        "rules": {
            "import/newline-after-import": "off",
            "no-use-extend-native/no-use-extend-native": "off"
        }
    },
    "nyc": {
        "reporter": [
            "html",
            "lcov",
            "text"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
