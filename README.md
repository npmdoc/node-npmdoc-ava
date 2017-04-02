# api documentation for  [ava (v0.18.2)](https://ava.li)  [![npm package](https://img.shields.io/npm/v/npmdoc-ava.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ava) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ava.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ava)
#### Futuristic test runner 🚀

[![NPM](https://nodei.co/npm/ava.png?downloads=true)](https://www.npmjs.com/package/ava)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ava/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ava_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ava/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-ava/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "email": "sindresorhus@gmail.com",
        "url": "sindresorhus.com"
    },
    "bin": {
        "ava": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/avajs/ava/issues"
    },
    "dependencies": {
        "@ava/babel-preset-stage-4": "^1.0.0",
        "@ava/babel-preset-transform-test-files": "^2.0.0",
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
        "cli-truncate": "^0.2.0",
        "co-with-promise": "^4.6.0",
        "code-excerpt": "^2.1.0",
        "common-path-prefix": "^1.0.0",
        "convert-source-map": "^1.2.0",
        "core-assert": "^0.2.0",
        "currently-unhandled": "^0.4.1",
        "debug": "^2.2.0",
        "diff": "^3.0.1",
        "dot-prop": "^4.1.0",
        "empower-core": "^0.6.1",
        "equal-length": "^1.0.0",
        "figures": "^2.0.0",
        "find-cache-dir": "^0.1.1",
        "fn-name": "^2.0.0",
        "get-port": "^2.1.0",
        "globby": "^6.0.0",
        "has-flag": "^2.0.0",
        "ignore-by-default": "^1.0.0",
        "indent-string": "^3.0.0",
        "is-ci": "^1.0.7",
        "is-generator-fn": "^1.0.0",
        "is-obj": "^1.0.0",
        "is-observable": "^0.2.0",
        "is-promise": "^2.1.0",
        "jest-snapshot": "^18.1.0",
        "last-line-stream": "^1.0.0",
        "lodash.debounce": "^4.0.3",
        "lodash.difference": "^4.3.0",
        "lodash.flatten": "^4.2.0",
        "lodash.isequal": "^4.5.0",
        "loud-rejection": "^1.2.0",
        "matcher": "^0.1.1",
        "max-timeout": "^1.0.0",
        "md5-hex": "^2.0.0",
        "meow": "^3.7.0",
        "ms": "^0.7.1",
        "multimatch": "^2.1.0",
        "observable-to-promise": "^0.4.0",
        "option-chain": "^0.1.0",
        "package-hash": "^1.2.0",
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
        "time-require": "^0.1.2",
        "unique-temp-dir": "^1.0.0",
        "update-notifier": "^1.0.0"
    },
    "description": "Futuristic test runner 🚀",
    "devDependencies": {
        "babel-preset-react": "^6.5.0",
        "cli-table2": "^0.2.0",
        "coveralls": "^2.11.4",
        "delay": "^1.3.0",
        "execa": "^0.6.0",
        "flow-bin": "^0.38.0",
        "get-stream": "^3.0.0",
        "git-branch": "^0.3.0",
        "has-ansi": "^2.0.0",
        "inquirer": "^2.0.0",
        "is-array-sorted": "^1.0.0",
        "lolex": "^1.4.0",
        "mkdirp": "^0.5.1",
        "nyc": "^10.0.0",
        "pify": "^2.3.0",
        "proxyquire": "^1.7.4",
        "rimraf": "^2.5.0",
        "signal-exit": "^3.0.0",
        "sinon": "^1.17.2",
        "source-map-fixtures": "^2.1.0",
        "tap": "^10.0.0",
        "temp-write": "^3.1.0",
        "touch": "^1.0.0",
        "xo": "^0.17.0",
        "zen-observable": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "79253d1636077034a2780bb55b5c3e6c3d7f312f",
        "tarball": "https://registry.npmjs.org/ava/-/ava-0.18.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib",
        "*.js",
        "*.js.flow",
        "types/generated.d.ts"
    ],
    "gitHead": "98dded553c8c213739cea9743ab4662f40d3125a",
    "homepage": "https://ava.li",
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
    "license": "MIT",
    "maintainers": [
        {
            "name": "ava",
            "email": "npm@ava.li"
        },
        {
            "name": "jamestalmage",
            "email": "james@talmage.io"
        },
        {
            "name": "jfmengels",
            "email": "jfm.engels@gmail.com"
        },
        {
            "name": "kevva",
            "email": "kevinmartensson@gmail.com"
        },
        {
            "name": "novemberborn",
            "email": "mark@novemberborn.net"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "sotojuan",
            "email": "imjuansoto@gmail.com"
        },
        {
            "name": "vdemedes",
            "email": "vdemedes@gmail.com"
        }
    ],
    "name": "ava",
    "nyc": {
        "reporter": [
            "html",
            "lcov",
            "text"
        ]
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/avajs/ava.git"
    },
    "scripts": {
        "make-ts": "node types/make.js",
        "prepublish": "npm run make-ts",
        "test": "xo && flow check test/flow-types && nyc tap --no-cov --timeout=150 --jobs=4 test/*.js test/reporters/*.js",
        "test-win": "tap --no-cov --reporter=classic --timeout=150 --jobs=4 test/*.js test/reporters/*.js",
        "visual": "node test/visual/run-visual-tests.js"
    },
    "typings": "types/generated.d.ts",
    "version": "0.18.2",
    "xo": {
        "esnext": true,
        "rules": {
            "import/newline-after-import": "off",
            "no-use-extend-native/no-use-extend-native": "off"
        }
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ava](#apidoc.module.ava)
1.  [function <span class="apidocSignatureSpan">ava.</span>ava_files (options)](#apidoc.element.ava.ava_files)
1.  [function <span class="apidocSignatureSpan">ava.</span>enhance_assert ('empower-core')](#apidoc.element.ava.enhance_assert)
1.  [function <span class="apidocSignatureSpan">ava.</span>runner (options)](#apidoc.element.ava.runner)
1.  object <span class="apidocSignatureSpan">ava.</span>_iron_node
1.  object <span class="apidocSignatureSpan">ava.</span>assert
1.  object <span class="apidocSignatureSpan">ava.</span>babel_config
1.  object <span class="apidocSignatureSpan">ava.</span>colors
1.  object <span class="apidocSignatureSpan">ava.</span>globals
1.  object <span class="apidocSignatureSpan">ava.</span>runner.prototype
1.  object <span class="apidocSignatureSpan">ava.</span>snapshot_state

#### [module ava._iron_node](#apidoc.module.ava._iron_node)
1.  [function <span class="apidocSignatureSpan">ava._iron_node.</span>workSpaceDirectory ()](#apidoc.element.ava._iron_node.workSpaceDirectory)
1.  object <span class="apidocSignatureSpan">ava._iron_node.</span>app

#### [module ava.assert](#apidoc.module.ava.assert)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>_snapshot (tree, optionalMessage, match, snapshotStateGetter)](#apidoc.element.ava.assert._snapshot)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>deepEqual (val, expected, msg)](#apidoc.element.ava.assert.deepEqual)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>fail ()](#apidoc.element.ava.assert.fail)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>false (val, msg)](#apidoc.element.ava.assert.false)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>falsy (val, msg)](#apidoc.element.ava.assert.falsy)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>ifError (err, msg)](#apidoc.element.ava.assert.ifError)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>is (val, expected, msg)](#apidoc.element.ava.assert.is)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>not (val, expected, msg)](#apidoc.element.ava.assert.not)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>notDeepEqual (val, expected, msg)](#apidoc.element.ava.assert.notDeepEqual)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>notRegex (contents, regex, msg)](#apidoc.element.ava.assert.notRegex)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>notThrows (fn, msg)](#apidoc.element.ava.assert.notThrows)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>pass (true, create(true, true, 'pass', msg, x.pass)](#apidoc.element.ava.assert.pass)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>regex (contents, regex, msg)](#apidoc.element.ava.assert.regex)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>snapshot (tree, optionalMessage)](#apidoc.element.ava.assert.snapshot)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>throws (fn, err, msg)](#apidoc.element.ava.assert.throws)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>true (val, msg)](#apidoc.element.ava.assert.true)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>truthy (val, msg)](#apidoc.element.ava.assert.truthy)

#### [module ava.ava_files](#apidoc.module.ava.ava_files)
1.  [function <span class="apidocSignatureSpan">ava.</span>ava_files (options)](#apidoc.element.ava.ava_files.ava_files)
1.  [function <span class="apidocSignatureSpan">ava.ava_files.</span>defaultExcludePatterns ()](#apidoc.element.ava.ava_files.defaultExcludePatterns)
1.  [function <span class="apidocSignatureSpan">ava.ava_files.</span>defaultIncludePatterns ()](#apidoc.element.ava.ava_files.defaultIncludePatterns)

#### [module ava.babel_config](#apidoc.module.ava.babel_config)
1.  [function <span class="apidocSignatureSpan">ava.babel_config.</span>build (babelConfig, powerAssert, filePath, code)](#apidoc.element.ava.babel_config.build)
1.  [function <span class="apidocSignatureSpan">ava.babel_config.</span>validate (conf)](#apidoc.element.ava.babel_config.validate)
1.  object <span class="apidocSignatureSpan">ava.babel_config.</span>presetHashes

#### [module ava.colors](#apidoc.module.ava.colors)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>duration ()](#apidoc.element.ava.colors.duration)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>error ()](#apidoc.element.ava.colors.error)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>errorSource ()](#apidoc.element.ava.colors.errorSource)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>errorStack ()](#apidoc.element.ava.colors.errorStack)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>information ()](#apidoc.element.ava.colors.information)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>pass ()](#apidoc.element.ava.colors.pass)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>skip ()](#apidoc.element.ava.colors.skip)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>stack ()](#apidoc.element.ava.colors.stack)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>title ()](#apidoc.element.ava.colors.title)
1.  [function <span class="apidocSignatureSpan">ava.colors.</span>todo ()](#apidoc.element.ava.colors.todo)

#### [module ava.enhance_assert](#apidoc.module.ava.enhance_assert)
1.  [function <span class="apidocSignatureSpan">ava.</span>enhance_assert ('empower-core')](#apidoc.element.ava.enhance_assert.enhance_assert)
1.  [function <span class="apidocSignatureSpan">ava.enhance_assert.</span>formatter ()](#apidoc.element.ava.enhance_assert.formatter)
1.  object <span class="apidocSignatureSpan">ava.enhance_assert.</span>NON_ENHANCED_PATTERNS
1.  object <span class="apidocSignatureSpan">ava.enhance_assert.</span>PATTERNS

#### [module ava.globals](#apidoc.module.ava.globals)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>clearTimeout ()](#apidoc.element.ava.globals.clearTimeout)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>now ()](#apidoc.element.ava.globals.now)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>setImmediate (callback, arg1, arg2, arg3)](#apidoc.element.ava.globals.setImmediate)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>setTimeout ()](#apidoc.element.ava.globals.setTimeout)
1.  object <span class="apidocSignatureSpan">ava.globals.</span>options

#### [module ava.runner](#apidoc.module.ava.runner)
1.  [function <span class="apidocSignatureSpan">ava.</span>runner (options)](#apidoc.element.ava.runner.runner)
1.  object <span class="apidocSignatureSpan">ava.runner.</span>_chainableMethods

#### [module ava.runner.prototype](#apidoc.module.ava.runner.prototype)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>after ()](#apidoc.element.ava.runner.prototype.after)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>afterEach ()](#apidoc.element.ava.runner.prototype.afterEach)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>always ()](#apidoc.element.ava.runner.prototype.always)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>before ()](#apidoc.element.ava.runner.prototype.before)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>beforeEach ()](#apidoc.element.ava.runner.prototype.beforeEach)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>cb ()](#apidoc.element.ava.runner.prototype.cb)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>failing ()](#apidoc.element.ava.runner.prototype.failing)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>only ()](#apidoc.element.ava.runner.prototype.only)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>serial ()](#apidoc.element.ava.runner.prototype.serial)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>skip ()](#apidoc.element.ava.runner.prototype.skip)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>test ()](#apidoc.element.ava.runner.prototype.test)
1.  [function <span class="apidocSignatureSpan">ava.runner.prototype.</span>todo ()](#apidoc.element.ava.runner.prototype.todo)

#### [module ava.snapshot_state](#apidoc.module.ava.snapshot_state)
1.  [function <span class="apidocSignatureSpan">ava.snapshot_state.</span>get (initializeState, globalsOptions)](#apidoc.element.ava.snapshot_state.get)
1.  object <span class="apidocSignatureSpan">ava.snapshot_state.</span>state



# <a name="apidoc.module.ava"></a>[module ava](#apidoc.module.ava)

#### <a name="apidoc.element.ava.ava_files"></a>[function <span class="apidocSignatureSpan">ava.</span>ava_files (options)](#apidoc.element.ava.ava_files)
- description and source-code
```javascript
class AvaFiles {
	constructor(options) {
		options = options || {};

		let files = (options.files || []).map(file => {
			// './' should be removed from the beginning of patterns because
			// otherwise they won't match change events from Chokidar
			if (file.slice(0, 2) === './') {
				return file.slice(2);
			}

			return file;
		});

		if (files.length === 0) {
			files = defaultIncludePatterns();
		}

		this.excludePatterns = defaultExcludePatterns();
		this.files = files;
		this.sources = options.sources || [];
		this.cwd = options.cwd || process.cwd();

		autoBind(this);
	}
	findTestFiles() {
		return handlePaths(this.files, this.excludePatterns, {
			cwd: this.cwd,
			cache: Object.create(null),
			statCache: Object.create(null),
			realpathCache: Object.create(null),
			symlinks: Object.create(null)
		});
	}
	findTestHelpers() {
		return handlePaths(defaultHelperPatterns(), ['!**/node_modules/**'], {
			cwd: this.cwd,
			includeUnderscoredFiles: true,
			cache: Object.create(null),
			statCache: Object.create(null),
			realpathCache: Object.create(null),
			symlinks: Object.create(null)
		});
	}
	isSource(filePath) {
		let mixedPatterns = [];
		const defaultIgnorePatterns = getDefaultIgnorePatterns();
		const overrideDefaultIgnorePatterns = [];

		let hasPositivePattern = false;
		this.sources.forEach(pattern => {
			mixedPatterns.push(pattern);

			// TODO: Why not just 'pattern[0] !== '!''?
			if (!hasPositivePattern && pattern[0] !== '!') {
				hasPositivePattern = true;
			}

			// Extract patterns that start with an ignored directory. These need to be
			// rematched separately.
			if (defaultIgnore.indexOf(pattern.split('/')[0]) >= 0) {
				overrideDefaultIgnorePatterns.push(pattern);
			}
		});

		// Same defaults as used for Chokidar
		if (!hasPositivePattern) {
			mixedPatterns = ['package.json', '**/*.js'].concat(mixedPatterns);
		}

		filePath = matchable(filePath);

		// Ignore paths outside the current working directory.
		// They can't be matched to a pattern.
		if (/^\.\.\//.test(filePath)) {
			return false;
		}

		const isSource = multimatch(filePath, mixedPatterns).length === 1;
		if (!isSource) {
			return false;
		}

		const isIgnored = multimatch(filePath, defaultIgnorePatterns).length === 1;
		if (!isIgnored) {
			return true;
		}

		const isErroneouslyIgnored = multimatch(filePath, overrideDefaultIgnorePatterns).length === 1;
		if (isErroneouslyIgnored) {
			return true;
		}

		return false;
	}
	isTest(filePath) {
		const excludePatterns = this.excludePatterns;
		const initialPatterns = this.files.concat(excludePatterns);

		// Like in 'api.js', tests must be '.js' files and not start with '_'
		if (path.extname(filePath) !== '.js' || path.basename(filePath)[0] === '_') {
			return false;
		}

		// Check if the entire path matches a pattern
		if (multimatch(matchable(filePath), initialPatterns).length === 1) {
			return true;
		}

		// Check if the path contains any directory components
		const dirname = path.dirname(filePath);
		if (dirname === '.') {
			return false;
		}

		// Compute all possible subpaths. Note that the dirname is assumed to be
		// relative to the working directory, without a leading './'.
		const subpaths = dirname.split(/[\\/]/).reduce((subpaths, component) => {
			const parent = subpaths[subpaths.length - 1];

			if (parent) {
				// Always use '/'' to makes multimatch consistent across platforms
				subpaths.push('${parent}/${component}');
			} else {
				subpaths.push(component);
			}

			return subpaths;
		}, []);

		// Check if any of the possible subpaths match a pattern. If so, generate a
		// new pattern with **/*.js.
		const recursivePatterns = subpaths
			.filter(subpath => multimatch(subpath, initialPatterns).length === 1)
			// Always use '/' to makes multimatch consistent across platforms
			.map(subpath => '${subpath}/**/*.js');

		// See if the entire path matches any of the subpaths patterns, taking the
		// excludePatterns into account. This mimicks the behavior in api.js
		return multimatch(matchable(filePath), recursivePatterns.concat(excludePattern ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.enhance_assert"></a>[function <span class="apidocSignatureSpan">ava.</span>enhance_assert ('empower-core')](#apidoc.element.ava.enhance_assert)
- description and source-code
```javascript
opts => {
	const empower = require('empower-core');
	const enhanced = empower(opts.assert, {
		destructive: false,
		onError: opts.onError,
		onSuccess: opts.onSuccess,
		patterns: PATTERNS,
		wrapOnlyPatterns: NON_ENHANCED_PATTERNS,
		bindReceiver: false
	});

	return enhanced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.runner"></a>[function <span class="apidocSignatureSpan">ava.</span>runner (options)](#apidoc.element.ava.runner)
- description and source-code
```javascript
class Runner extends EventEmitter {
	constructor(options) {
		super();

		options = options || {};

		this.results = [];
		this.tests = new TestCollection();
		this.hasStarted = false;
		this._bail = options.bail;
		this._serial = options.serial;
		this._match = options.match || [];
		this._addTestResult = this._addTestResult.bind(this);
		this._buildStats = this._buildStats.bind(this);
	}
	_addTest(title, opts, fn, args) {
		if (args) {
			if (fn.title) {
				title = fn.title.apply(fn, [title || ''].concat(args));
			}

			fn = wrapFunction(fn, args);
		}

		if (opts.type === 'test' && this._match.length > 0) {
			opts.exclusive = title !== null && matcher([title], this._match).length === 1;
		}

		const validationError = validateTest(title, fn, opts);
		if (validationError !== null) {
			throw new TypeError(validationError);
		}

		if (opts.todo) {
			fn = noop;
		}

		this.tests.add({
			metadata: opts,
			fn,
			title
		});
	}
	_addTestResult(result) {
		const test = result.result;
		const props = {
			duration: test.duration,
			title: test.title,
			error: result.reason,
			type: test.metadata.type,
			skip: test.metadata.skipped,
			todo: test.metadata.todo,
			failing: test.metadata.failing
		};

		this.results.push(result);
		this.emit('test', props);
	}
	_buildStats() {
		const stats = {
			testCount: 0,
			skipCount: 0,
			todoCount: 0
		};

		this.results
			.map(result => {
				return result.result;
			})
			.filter(test => {
				return test.metadata.type === 'test';
			})
			.forEach(test => {
				stats.testCount++;

				if (test.metadata.skipped) {
					stats.skipCount++;
				}

				if (test.metadata.todo) {
					stats.todoCount++;
				}
			});

		stats.failCount = this.results
			.filter(result => {
				return result.passed === false;
			})
			.length;

		stats.knownFailureCount = this.results
			.filter(result => {
				return result.passed === true && result.result.metadata.failing;
			})
			.length;

		stats.passCount = stats.testCount - stats.failCount - stats.skipCount - stats.todoCount;

		return stats;
	}
	run(options) {
		if (options.runOnlyExclusive && !this.tests.hasExclusive) {
			return Promise.resolve(null);
		}

		this.tests.on('test', this._addTestResult);

		this.hasStarted = true;

		return Promise.resolve(this.tests.build(this._bail).run()).then(this._buildStats);
	}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava._iron_node"></a>[module ava._iron_node](#apidoc.module.ava._iron_node)

#### <a name="apidoc.element.ava._iron_node.workSpaceDirectory"></a>[function <span class="apidocSignatureSpan">ava._iron_node.</span>workSpaceDirectory ()](#apidoc.element.ava._iron_node.workSpaceDirectory)
- description and source-code
```javascript
workSpaceDirectory = function () {
		return __dirname;
	}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava.assert"></a>[module ava.assert](#apidoc.module.ava.assert)

#### <a name="apidoc.element.ava.assert._snapshot"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>_snapshot (tree, optionalMessage, match, snapshotStateGetter)](#apidoc.element.ava.assert._snapshot)
- description and source-code
```javascript
_snapshot = function (tree, optionalMessage, match, snapshotStateGetter) {
	// Set defaults - this allows tests to mock deps easily
	const toMatchSnapshot = match || jestSnapshot.toMatchSnapshot;
	const getState = snapshotStateGetter || snapshotState.get;

	const state = getState();

	const context = {
		dontThrow() {},
		currentTestName: this.title,
		snapshotState: state
	};

	// Symbols can't be serialized and saved in a snapshot, that's why tree
	// is saved in the '__ava_react_jsx' prop, so that JSX can be detected later
	const serializedTree = tree.$$typeof === Symbol.for('react.test.json') ? {__ava_react_jsx: tree} : tree; // eslint-disable-line
 camelcase
	const result = toMatchSnapshot.call(context, JSON.stringify(serializedTree));

	let message = 'Please check your code or --update-snapshots';

	if (optionalMessage) {
		message += '\n\n' + indentString(optionalMessage, 2);
	}

	state.save();

	let expected;

	if (result.expected) {
		// JSON in a snapshot is surrounded with '"', because jest-snapshot
		// serializes snapshot values too, so it ends up double JSON encoded
		expected = JSON.parse(result.expected.slice(1).slice(0, -1));
		// Define a '$$typeof' symbol, so that pretty-format detects it as React tree
		if (expected.__ava_react_jsx) { // eslint-disable-line camelcase
			expected = expected.__ava_react_jsx; // eslint-disable-line camelcase
			Object.defineProperty(expected, '$$typeof', {value: Symbol.for('react.test.json')});
		}
	}

	test(result.pass, create(tree, expected, 'snapshot', message, x.snapshot));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.assert.deepEqual"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>deepEqual (val, expected, msg)](#apidoc.element.ava.assert.deepEqual)
- description and source-code
```javascript
(val, expected, msg) => {
	test(deepEqual(val, expected), create(val, expected, '===', msg, x.deepEqual));
}
```
- example usage
```shell
...

## Test syntax

'''js
import test from 'ava';

test(t => {
	t.deepEqual([1, 2], [1, 2]);
});
'''

## Usage

### Add AVA to your project
...
```

#### <a name="apidoc.element.ava.assert.fail"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>fail ()](#apidoc.element.ava.assert.fail)
- description and source-code
```javascript
msg => {
	msg = msg || 'Test failed via t.fail()';
	test(false, create(false, false, 'fail', msg, x.fail));
}
```
- example usage
```shell
...

### Running specific tests

During development it can be helpful to only run a few specific tests. This can be accomplished using the '.only' modifier:

'''js
test('will not be run', t => {
	t.fail();
});

test.only('will be run', t => {
	t.pass();
});
'''
...
```

#### <a name="apidoc.element.ava.assert.false"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>false (val, msg)](#apidoc.element.ava.assert.false)
- description and source-code
```javascript
(val, msg) => {
	test(val === false, create(val, false, '===', msg, x.false));
}
```
- example usage
```shell
...

Assert that 'value' is falsy.

### '.true(value, [message])'

Assert that 'value' is 'true'.

### '.false(value, [message])'

Assert that 'value' is 'false'.

### '.is(value, expected, [message])'

Assert that 'value' is equal to 'expected'.
...
```

#### <a name="apidoc.element.ava.assert.falsy"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>falsy (val, msg)](#apidoc.element.ava.assert.falsy)
- description and source-code
```javascript
(val, msg) => {
	test(!val, create(val, false, '==', msg, x.falsy));
}
```
- example usage
```shell
...

Failing assertion.

### '.truthy(value, [message])'

Assert that 'value' is truthy.

### '.falsy(value, [message])'

Assert that 'value' is falsy.

### '.true(value, [message])'

Assert that 'value' is 'true'.
...
```

#### <a name="apidoc.element.ava.assert.ifError"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>ifError (err, msg)](#apidoc.element.ava.assert.ifError)
- description and source-code
```javascript
(err, msg) => {
	test(!err, create(err, 'Error', '!==', msg, x.ifError));
}
```
- example usage
```shell
...

Assert that 'contents' matches 'regex'.

### '.notRegex(contents, regex, [message])'

Assert that 'contents' does not match 'regex'.

### '.ifError(error, [message])'

Assert that 'error' is falsy.

### '.snapshot(contents, [message])'

Make a snapshot of the stringified 'contents'.
...
```

#### <a name="apidoc.element.ava.assert.is"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>is (val, expected, msg)](#apidoc.element.ava.assert.is)
- description and source-code
```javascript
(val, expected, msg) => {
	test(val === expected, create(val, expected, '===', msg, x.is));
}
```
- example usage
```shell
...
test('foo', t => {
	t.pass();
});

test('bar', async t => {
	const bar = Promise.resolve('bar');

	t.is(await bar, 'bar');
});
'''

### Run it

'''console
$ npm test
...
```

#### <a name="apidoc.element.ava.assert.not"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>not (val, expected, msg)](#apidoc.element.ava.assert.not)
- description and source-code
```javascript
(val, expected, msg) => {
	test(val !== expected, create(val, expected, '!==', msg, x.not));
}
```
- example usage
```shell
...

Assert that 'value' is 'false'.

### '.is(value, expected, [message])'

Assert that 'value' is equal to 'expected'.

### '.not(value, expected, [message])'

Assert that 'value' is not equal to 'expected'.

### '.deepEqual(value, expected, [message])'

Assert that 'value' is deep equal to 'expected'. This is based on [Lodash' 'isEqual()'](https://lodash.com/docs/4.17.4#isEqual):
...
```

#### <a name="apidoc.element.ava.assert.notDeepEqual"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>notDeepEqual (val, expected, msg)](#apidoc.element.ava.assert.notDeepEqual)
- description and source-code
```javascript
(val, expected, msg) => {
	test(!deepEqual(val, expected), create(val, expected, '!==', msg, x.notDeepEqual));
}
```
- example usage
```shell
...

Assert that 'value' is deep equal to 'expected'. This is based on [Lodash' 'isEqual()'](https://lodash.com/docs/4.17.4#isEqual):

> Performs a deep comparison between two values to determine if they are equivalent.
>
> *Note*: This method supports comparing arrays, array buffers, booleans, date objects, error objects, maps, numbers, 'Object' objects
, regexes, sets, strings, symbols, and typed arrays. 'Object' objects are compared by their own, not inherited, enumerable properties
. Functions and DOM nodes are compared by strict equality, i.e. '==='.

### '.notDeepEqual(value, expected, [message])'

Assert that 'value' is not deep equal to 'expected'. The inverse of '.deepEqual()'.

### '.throws(function|promise, [error, [message]])'

Assert that 'function' throws an error, or 'promise' rejects with an error.
...
```

#### <a name="apidoc.element.ava.assert.notRegex"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>notRegex (contents, regex, msg)](#apidoc.element.ava.assert.notRegex)
- description and source-code
```javascript
(contents, regex, msg) => {
	test(!regex.test(contents), create(regex, contents, '!==', msg, x.notRegex));
}
```
- example usage
```shell
...

Assert that 'function' does not throw an error or that 'promise' does not reject with an error.

### '.regex(contents, regex, [message])'

Assert that 'contents' matches 'regex'.

### '.notRegex(contents, regex, [message])'

Assert that 'contents' does not match 'regex'.

### '.ifError(error, [message])'

Assert that 'error' is falsy.
...
```

#### <a name="apidoc.element.ava.assert.notThrows"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>notThrows (fn, msg)](#apidoc.element.ava.assert.notThrows)
- description and source-code
```javascript
(fn, msg) => {
	if (isObservable(fn)) {
		fn = observableToPromise(fn);
	}

	if (isPromise(fn)) {
		return fn
			.catch(err => {
				x.notThrows(() => {
					throw err;
				}, msg);
			});
	}

	if (typeof fn !== 'function') {
		throw new TypeError('t.notThrows must be called with a function, Promise, or Observable');
	}

	try {
		assert.doesNotThrow(fn, msg);
	} catch (err) {
		test(false, create(err.actual, err.expected, 'notThrows', err.message, x.notThrows));
	}
}
```
- example usage
```shell
...

test('rejects', async t => {
	const error = await t.throws(promise);
	t.is(error.message, '🦄');
});
'''

### '.notThrows(function|promise, [message])'

Assert that 'function' does not throw an error or that 'promise' does not reject with an error.

### '.regex(contents, regex, [message])'

Assert that 'contents' matches 'regex'.
...
```

#### <a name="apidoc.element.ava.assert.pass"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>pass (true, create(true, true, 'pass', msg, x.pass)](#apidoc.element.ava.assert.pass)
- description and source-code
```javascript
msg => {
	test(true, create(true, true, 'pass', msg, x.pass));
}
```
- example usage
```shell
...

Create a file named 'test.js' in the project root directory:

'''js
import test from 'ava';

test('foo', t => {
	t.pass();
});

test('bar', async t => {
	const bar = Promise.resolve('bar');

	t.is(await bar, 'bar');
});
...
```

#### <a name="apidoc.element.ava.assert.regex"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>regex (contents, regex, msg)](#apidoc.element.ava.assert.regex)
- description and source-code
```javascript
(contents, regex, msg) => {
	test(regex.test(contents), create(regex, contents, '===', msg, x.regex));
}
```
- example usage
```shell
...
});
'''

### '.notThrows(function|promise, [message])'

Assert that 'function' does not throw an error or that 'promise' does not reject with an error.

### '.regex(contents, regex, [message])'

Assert that 'contents' matches 'regex'.

### '.notRegex(contents, regex, [message])'

Assert that 'contents' does not match 'regex'.
...
```

#### <a name="apidoc.element.ava.assert.snapshot"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>snapshot (tree, optionalMessage)](#apidoc.element.ava.assert.snapshot)
- description and source-code
```javascript
snapshot = function (tree, optionalMessage) {
	x._snapshot.call(this, tree, optionalMessage);
}
```
- example usage
```shell
...

Assert that 'contents' does not match 'regex'.

### '.ifError(error, [message])'

Assert that 'error' is falsy.

### '.snapshot(contents, [message])'

Make a snapshot of the stringified 'contents'.

## Snapshot testing

Snapshot testing comes as another kind of assertion and uses [jest-snapshot](https://facebook.github.io/jest/blog/2016/07/27/jest
-14.html) under the hood.
...
```

#### <a name="apidoc.element.ava.assert.throws"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>throws (fn, err, msg)](#apidoc.element.ava.assert.throws)
- description and source-code
```javascript
(fn, err, msg) => {
	if (isObservable(fn)) {
		fn = observableToPromise(fn);
	}

	if (isPromise(fn)) {
		return fn
			.then(() => {
				x.throws(noop, err, msg);
			}, fnErr => {
				return x.throws(() => {
					throw fnErr;
				}, err, msg);
			});
	}

	if (typeof fn !== 'function') {
		throw new TypeError('t.throws must be called with a function, Promise, or Observable');
	}

	try {
		if (typeof err === 'string') {
			const errMsg = err;
			err = err => err.message === errMsg;
		}

		let result;

		assert.throws(() => {
			try {
				fn();
			} catch (err) {
				result = err;
				throw err;
			}
		}, err, msg);

		return result;
	} catch (err) {
		test(false, create(err.actual, err.expected, 'throws', err.message, x.throws));
	}
}
```
- example usage
```shell
...
>
> *Note*: This method supports comparing arrays, array buffers, booleans, date objects, error objects, maps, numbers, 'Object' objects
, regexes, sets, strings, symbols, and typed arrays. 'Object' objects are compared by their own, not inherited, enumerable properties
. Functions and DOM nodes are compared by strict equality, i.e. '==='.

### '.notDeepEqual(value, expected, [message])'

Assert that 'value' is not deep equal to 'expected'. The inverse of '.deepEqual()'.

### '.throws(function|promise, [error, [message]])'

Assert that 'function' throws an error, or 'promise' rejects with an error.

'error' can be an error constructor, error message, regex matched against the error message, or validation function.

Returns the error thrown by 'function' or a promise for the rejection reason of the specified 'promise'.
...
```

#### <a name="apidoc.element.ava.assert.true"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>true (val, msg)](#apidoc.element.ava.assert.true)
- description and source-code
```javascript
(val, msg) => {
	test(val === true, create(val, true, '===', msg, x.true));
}
```
- example usage
```shell
...
These won't:

'''js
test(t => {
	t.plan(2);

	for (let i = 0; i < 3; i++) {
		t.true(i < 3);
	}
}); // Fails, 3 assertions are executed which is too many

test(t => {
	t.plan(1);

	someAsyncFunction(() => {
...
```

#### <a name="apidoc.element.ava.assert.truthy"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>truthy (val, msg)](#apidoc.element.ava.assert.truthy)
- description and source-code
```javascript
(val, msg) => {
	test(val, create(val, true, '==', msg, x.truthy));
}
```
- example usage
```shell
...

## Assertions

Assertions are mixed into the [execution object](#t) provided to each test implementation:

'''js
test(t => {
	t.truthy('unicorn'); // Assertion
});
'''

If multiple assertion failures are encountered within a single test, AVA will only display the *first* one.

### '.pass([message])'
...
```



# <a name="apidoc.module.ava.ava_files"></a>[module ava.ava_files](#apidoc.module.ava.ava_files)

#### <a name="apidoc.element.ava.ava_files.ava_files"></a>[function <span class="apidocSignatureSpan">ava.</span>ava_files (options)](#apidoc.element.ava.ava_files.ava_files)
- description and source-code
```javascript
class AvaFiles {
	constructor(options) {
		options = options || {};

		let files = (options.files || []).map(file => {
			// './' should be removed from the beginning of patterns because
			// otherwise they won't match change events from Chokidar
			if (file.slice(0, 2) === './') {
				return file.slice(2);
			}

			return file;
		});

		if (files.length === 0) {
			files = defaultIncludePatterns();
		}

		this.excludePatterns = defaultExcludePatterns();
		this.files = files;
		this.sources = options.sources || [];
		this.cwd = options.cwd || process.cwd();

		autoBind(this);
	}
	findTestFiles() {
		return handlePaths(this.files, this.excludePatterns, {
			cwd: this.cwd,
			cache: Object.create(null),
			statCache: Object.create(null),
			realpathCache: Object.create(null),
			symlinks: Object.create(null)
		});
	}
	findTestHelpers() {
		return handlePaths(defaultHelperPatterns(), ['!**/node_modules/**'], {
			cwd: this.cwd,
			includeUnderscoredFiles: true,
			cache: Object.create(null),
			statCache: Object.create(null),
			realpathCache: Object.create(null),
			symlinks: Object.create(null)
		});
	}
	isSource(filePath) {
		let mixedPatterns = [];
		const defaultIgnorePatterns = getDefaultIgnorePatterns();
		const overrideDefaultIgnorePatterns = [];

		let hasPositivePattern = false;
		this.sources.forEach(pattern => {
			mixedPatterns.push(pattern);

			// TODO: Why not just 'pattern[0] !== '!''?
			if (!hasPositivePattern && pattern[0] !== '!') {
				hasPositivePattern = true;
			}

			// Extract patterns that start with an ignored directory. These need to be
			// rematched separately.
			if (defaultIgnore.indexOf(pattern.split('/')[0]) >= 0) {
				overrideDefaultIgnorePatterns.push(pattern);
			}
		});

		// Same defaults as used for Chokidar
		if (!hasPositivePattern) {
			mixedPatterns = ['package.json', '**/*.js'].concat(mixedPatterns);
		}

		filePath = matchable(filePath);

		// Ignore paths outside the current working directory.
		// They can't be matched to a pattern.
		if (/^\.\.\//.test(filePath)) {
			return false;
		}

		const isSource = multimatch(filePath, mixedPatterns).length === 1;
		if (!isSource) {
			return false;
		}

		const isIgnored = multimatch(filePath, defaultIgnorePatterns).length === 1;
		if (!isIgnored) {
			return true;
		}

		const isErroneouslyIgnored = multimatch(filePath, overrideDefaultIgnorePatterns).length === 1;
		if (isErroneouslyIgnored) {
			return true;
		}

		return false;
	}
	isTest(filePath) {
		const excludePatterns = this.excludePatterns;
		const initialPatterns = this.files.concat(excludePatterns);

		// Like in 'api.js', tests must be '.js' files and not start with '_'
		if (path.extname(filePath) !== '.js' || path.basename(filePath)[0] === '_') {
			return false;
		}

		// Check if the entire path matches a pattern
		if (multimatch(matchable(filePath), initialPatterns).length === 1) {
			return true;
		}

		// Check if the path contains any directory components
		const dirname = path.dirname(filePath);
		if (dirname === '.') {
			return false;
		}

		// Compute all possible subpaths. Note that the dirname is assumed to be
		// relative to the working directory, without a leading './'.
		const subpaths = dirname.split(/[\\/]/).reduce((subpaths, component) => {
			const parent = subpaths[subpaths.length - 1];

			if (parent) {
				// Always use '/'' to makes multimatch consistent across platforms
				subpaths.push('${parent}/${component}');
			} else {
				subpaths.push(component);
			}

			return subpaths;
		}, []);

		// Check if any of the possible subpaths match a pattern. If so, generate a
		// new pattern with **/*.js.
		const recursivePatterns = subpaths
			.filter(subpath => multimatch(subpath, initialPatterns).length === 1)
			// Always use '/' to makes multimatch consistent across platforms
			.map(subpath => '${subpath}/**/*.js');

		// See if the entire path matches any of the subpaths patterns, taking the
		// excludePatterns into account. This mimicks the behavior in api.js
		return multimatch(matchable(filePath), recursivePatterns.concat(excludePattern ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.ava_files.defaultExcludePatterns"></a>[function <span class="apidocSignatureSpan">ava.ava_files.</span>defaultExcludePatterns ()](#apidoc.element.ava.ava_files.defaultExcludePatterns)
- description and source-code
```javascript
() => [
	'!**/node_modules/**',
	'!**/fixtures/**',
	'!**/helpers/**'
]
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.ava_files.defaultIncludePatterns"></a>[function <span class="apidocSignatureSpan">ava.ava_files.</span>defaultIncludePatterns ()](#apidoc.element.ava.ava_files.defaultIncludePatterns)
- description and source-code
```javascript
() => [
	'test.js',
	'test-*.js',
	'test',
	'**/__tests__',
	'**/*.test.js'
]
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava.babel_config"></a>[module ava.babel_config](#apidoc.module.ava.babel_config)

#### <a name="apidoc.element.ava.babel_config.build"></a>[function <span class="apidocSignatureSpan">ava.babel_config.</span>build (babelConfig, powerAssert, filePath, code)](#apidoc.element.ava.babel_config.build)
- description and source-code
```javascript
function build(babelConfig, powerAssert, filePath, code) {
	babelConfig = validate(babelConfig);

	let options;

	if (babelConfig === 'default') {
		options = {
			babelrc: false,
			presets: [stage4]
		};
	} else if (babelConfig === 'inherit') {
		options = {
			babelrc: true
		};
	} else {
		options = {
			babelrc: false
		};

		Object.assign(options, babelConfig);
	}

	const sourceMap = getSourceMap(filePath, code);

	Object.assign(options, {
		inputSourceMap: sourceMap,
		filename: filePath,
		sourceMaps: true,
		ast: false
	});

	if (!options.presets) {
		options.presets = [];
	}
	options.presets.push(makeTransformTestFiles(powerAssert));

	return options;
}
```
- example usage
```shell
...
	_init() {
		this.babel = require('babel-core');
		return this._transform;
	}
	_transform(code, filePath, hash) {
		code = code.toString();

		const options = babelConfigHelper.build(this.babelConfig, this.powerAssert, filePath, code);
		const result = this.babel.transform(code, options);

		// Save source map
		const mapPath = path.join(this.cacheDirPath, '${hash}.js.map');
		fs.writeFileSync(mapPath, JSON.stringify(result.map));

		// Append source map comment to transformed code
...
```

#### <a name="apidoc.element.ava.babel_config.validate"></a>[function <span class="apidocSignatureSpan">ava.babel_config.</span>validate (conf)](#apidoc.element.ava.babel_config.validate)
- description and source-code
```javascript
function validate(conf) {
	if (conf === undefined || conf === null) {
		conf = 'default';
	}

	// Check for valid babel config shortcuts (can be either 'default' or 'inherit')
	const isValidShortcut = conf === 'default' || conf === 'inherit';

	if (!conf || (typeof conf === 'string' && !isValidShortcut)) {
		let message = colors.error(figures.cross);
		message += ' Unexpected Babel configuration for AVA. ';
		message += 'See ' + chalk.underline('https://github.com/avajs/ava#es2015-support') + ' for allowed values.';

		throw new Error(message);
	}

	return conf;
}
```
- example usage
```shell
...

class CachingPrecompiler {
	constructor(options) {
		autoBind(this);

		options = options || {};

		this.babelConfig = babelConfigHelper.validate(options.babel);
		this.cacheDirPath = options.path;
		this.powerAssert = Boolean(options.powerAssert);
		this.fileHashes = {};
		this.transform = this._createTransform();
	}
	precompileFile(filePath) {
		if (!this.fileHashes[filePath]) {
...
```



# <a name="apidoc.module.ava.colors"></a>[module ava.colors](#apidoc.module.ava.colors)

#### <a name="apidoc.element.ava.colors.duration"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>duration ()](#apidoc.element.ava.colors.duration)
- description and source-code
```javascript
duration = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.colors.error"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>error ()](#apidoc.element.ava.colors.error)
- description and source-code
```javascript
error = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
...
		conf = 'default';
	}

	// Check for valid babel config shortcuts (can be either 'default' or 'inherit')
	const isValidShortcut = conf === 'default' || conf === 'inherit';

	if (!conf || (typeof conf === 'string' && !isValidShortcut)) {
		let message = colors.error(figures.cross);
		message += ' Unexpected Babel configuration for AVA. ';
		message += 'See ' + chalk.underline('https://github.com/avajs/ava#es2015-support') + ' for allowed values.';

		throw new Error(message);
	}

	return conf;
...
```

#### <a name="apidoc.element.ava.colors.errorSource"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>errorSource ()](#apidoc.element.ava.colors.errorSource)
- description and source-code
```javascript
errorSource = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.colors.errorStack"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>errorStack ()](#apidoc.element.ava.colors.errorStack)
- description and source-code
```javascript
errorStack = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.colors.information"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>information ()](#apidoc.element.ava.colors.information)
- description and source-code
```javascript
information = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.colors.pass"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>pass ()](#apidoc.element.ava.colors.pass)
- description and source-code
```javascript
pass = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
...

Create a file named 'test.js' in the project root directory:

'''js
import test from 'ava';

test('foo', t => {
	t.pass();
});

test('bar', async t => {
	const bar = Promise.resolve('bar');

	t.is(await bar, 'bar');
});
...
```

#### <a name="apidoc.element.ava.colors.skip"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>skip ()](#apidoc.element.ava.colors.skip)
- description and source-code
```javascript
skip = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
...
'''

### Skipping tests

Sometimes failing tests can be hard to fix. You can tell AVA to skip these tests using the '.skip' modifier. They'll still be shown
 in the output (as having been skipped) but are never run.

'''js
test.skip('will not be run', t => {
	t.fail();
});
'''

You must specify the implementation function.

### Test placeholders ("todo")
...
```

#### <a name="apidoc.element.ava.colors.stack"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>stack ()](#apidoc.element.ava.colors.stack)
- description and source-code
```javascript
stack = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.colors.title"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>title ()](#apidoc.element.ava.colors.title)
- description and source-code
```javascript
title = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.colors.todo"></a>[function <span class="apidocSignatureSpan">ava.colors.</span>todo ()](#apidoc.element.ava.colors.todo)
- description and source-code
```javascript
todo = function () {
		return applyStyle.apply(builder, arguments);
	}
```
- example usage
```shell
...
You must specify the implementation function.

### Test placeholders ("todo")

You can use the '.todo' modifier when you're planning to write a test. Like skipped tests these placeholders are shown in the output
. They only require a title; you cannot specify the implementation function.

'''js
test.todo('will think about writing this later');
'''

### Failing tests

You can use the '.failing' modifier to document issues with your code that need to be fixed. Failing tests are run just like normal
 ones, but they are expected to fail, and will not break your build when they do. If a test marked as failing actually passes, it
 will be reported as an error and fail the build with a helpful message instructing you to remove the '.failing' modifier.

This allows you to merge '.failing' tests before a fix is implemented without breaking CI. This is a great way to recognize good
 bug report PR's with a commit credit, even if the reporter is unable to actually fix the problem.
...
```



# <a name="apidoc.module.ava.enhance_assert"></a>[module ava.enhance_assert](#apidoc.module.ava.enhance_assert)

#### <a name="apidoc.element.ava.enhance_assert.enhance_assert"></a>[function <span class="apidocSignatureSpan">ava.</span>enhance_assert ('empower-core')](#apidoc.element.ava.enhance_assert.enhance_assert)
- description and source-code
```javascript
opts => {
	const empower = require('empower-core');
	const enhanced = empower(opts.assert, {
		destructive: false,
		onError: opts.onError,
		onSuccess: opts.onSuccess,
		patterns: PATTERNS,
		wrapOnlyPatterns: NON_ENHANCED_PATTERNS,
		bindReceiver: false
	});

	return enhanced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.enhance_assert.formatter"></a>[function <span class="apidocSignatureSpan">ava.enhance_assert.</span>formatter ()](#apidoc.element.ava.enhance_assert.formatter)
- description and source-code
```javascript
() => {
	return context => {
		const ast = JSON.parse(context.source.ast);
		const tokens = JSON.parse(context.source.tokens);
		const args = context.args[0].events;

		return args
			.map(arg => {
				const range = getNode(ast, arg.espath).range;
				return [computeStatement(tokens, range), arg.value];
			})
			.reverse();
	};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava.globals"></a>[module ava.globals](#apidoc.module.ava.globals)

#### <a name="apidoc.element.ava.globals.clearTimeout"></a>[function <span class="apidocSignatureSpan">ava.globals.</span>clearTimeout ()](#apidoc.element.ava.globals.clearTimeout)
- description and source-code
```javascript
clearTimeout = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.globals.now"></a>[function <span class="apidocSignatureSpan">ava.globals.</span>now ()](#apidoc.element.ava.globals.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.globals.setImmediate"></a>[function <span class="apidocSignatureSpan">ava.globals.</span>setImmediate (callback, arg1, arg2, arg3)](#apidoc.element.ava.globals.setImmediate)
- description and source-code
```javascript
setImmediate = function (callback, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var i, args;

  switch (arguments.length) {
    // fast cases
    case 1:
      break;
    case 2:
      args = [arg1];
      break;
    case 3:
      args = [arg1, arg2];
      break;
    default:
      args = [arg1, arg2, arg3];
      for (i = 4; i < arguments.length; i++)
        // extend array dynamically, makes .apply run much faster in v6.0.0
        args[i - 1] = arguments[i];
      break;
  }
  return createImmediate(args, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.globals.setTimeout"></a>[function <span class="apidocSignatureSpan">ava.globals.</span>setTimeout ()](#apidoc.element.ava.globals.setTimeout)
- description and source-code
```javascript
setTimeout = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava.runner"></a>[module ava.runner](#apidoc.module.ava.runner)

#### <a name="apidoc.element.ava.runner.runner"></a>[function <span class="apidocSignatureSpan">ava.</span>runner (options)](#apidoc.element.ava.runner.runner)
- description and source-code
```javascript
class Runner extends EventEmitter {
	constructor(options) {
		super();

		options = options || {};

		this.results = [];
		this.tests = new TestCollection();
		this.hasStarted = false;
		this._bail = options.bail;
		this._serial = options.serial;
		this._match = options.match || [];
		this._addTestResult = this._addTestResult.bind(this);
		this._buildStats = this._buildStats.bind(this);
	}
	_addTest(title, opts, fn, args) {
		if (args) {
			if (fn.title) {
				title = fn.title.apply(fn, [title || ''].concat(args));
			}

			fn = wrapFunction(fn, args);
		}

		if (opts.type === 'test' && this._match.length > 0) {
			opts.exclusive = title !== null && matcher([title], this._match).length === 1;
		}

		const validationError = validateTest(title, fn, opts);
		if (validationError !== null) {
			throw new TypeError(validationError);
		}

		if (opts.todo) {
			fn = noop;
		}

		this.tests.add({
			metadata: opts,
			fn,
			title
		});
	}
	_addTestResult(result) {
		const test = result.result;
		const props = {
			duration: test.duration,
			title: test.title,
			error: result.reason,
			type: test.metadata.type,
			skip: test.metadata.skipped,
			todo: test.metadata.todo,
			failing: test.metadata.failing
		};

		this.results.push(result);
		this.emit('test', props);
	}
	_buildStats() {
		const stats = {
			testCount: 0,
			skipCount: 0,
			todoCount: 0
		};

		this.results
			.map(result => {
				return result.result;
			})
			.filter(test => {
				return test.metadata.type === 'test';
			})
			.forEach(test => {
				stats.testCount++;

				if (test.metadata.skipped) {
					stats.skipCount++;
				}

				if (test.metadata.todo) {
					stats.todoCount++;
				}
			});

		stats.failCount = this.results
			.filter(result => {
				return result.passed === false;
			})
			.length;

		stats.knownFailureCount = this.results
			.filter(result => {
				return result.passed === true && result.result.metadata.failing;
			})
			.length;

		stats.passCount = stats.testCount - stats.failCount - stats.skipCount - stats.todoCount;

		return stats;
	}
	run(options) {
		if (options.runOnlyExclusive && !this.tests.hasExclusive) {
			return Promise.resolve(null);
		}

		this.tests.on('test', this._addTestResult);

		this.hasStarted = true;

		return Promise.resolve(this.tests.build(this._bail).run()).then(this._buildStats);
	}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava.runner.prototype"></a>[module ava.runner.prototype](#apidoc.module.ava.runner.prototype)

#### <a name="apidoc.element.ava.runner.prototype.after"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>after ()](#apidoc.element.ava.runner.prototype.after)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
});
'''

### Before & after hooks

AVA lets you register hooks that are run before and after your tests. This allows you to run setup and/or teardown code.

'test.before()' registers a hook to be run before the first test in your test file. Similarly 'test.after()' registers a hook to
 be run after the last test. Use 'test.after.always()' to register a hook that will **always** run once your tests and other hooks
 complete. '.always()' hooks run regardless of whether there were earlier failures, so they are ideal for cleanup tasks. There are
 two exceptions to this however. If you use '--fail-fast' AVA will stop testing as soon as a failure occurs, and it won't run any
 hooks including the '.always()' hooks. Uncaught exceptions will crash your tests, possibly preventing '.always()' hooks from running
.

'test.beforeEach()' registers a hook to be run before each test in your test file. Similarly 'test.afterEach()' a hook to be run
 after each test. Use 'test.afterEach.always()' to register an after hook that is called even if other test hooks, or the test itself
, fail. '.always()' hooks are ideal for cleanup tasks.

**Note**: If the '--fail-fast' flag is specified, AVA will stop after the first test failure and the '.always' hook will **not**
run.

Like 'test()' these methods take an optional title and a callback function. The title is shown if your hook fails to execute. The
 callback is called with an [execution object](#t).
...
```

#### <a name="apidoc.element.ava.runner.prototype.afterEach"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>afterEach ()](#apidoc.element.ava.runner.prototype.afterEach)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...

### Before & after hooks

AVA lets you register hooks that are run before and after your tests. This allows you to run setup and/or teardown code.

'test.before()' registers a hook to be run before the first test in your test file. Similarly 'test.after()' registers a hook to
 be run after the last test. Use 'test.after.always()' to register a hook that will **always** run once your tests and other hooks
 complete. '.always()' hooks run regardless of whether there were earlier failures, so they are ideal for cleanup tasks. There are
 two exceptions to this however. If you use '--fail-fast' AVA will stop testing as soon as a failure occurs, and it won't run any
 hooks including the '.always()' hooks. Uncaught exceptions will crash your tests, possibly preventing '.always()' hooks from running
.

'test.beforeEach()' registers a hook to be run before each test in your test file. Similarly 'test.afterEach()' a hook to be run
 after each test. Use 'test.afterEach.always()' to register an after hook that is called even if other test hooks, or the test itself
, fail. '.always()' hooks are ideal for cleanup tasks.

**Note**: If the '--fail-fast' flag is specified, AVA will stop after the first test failure and the '.always' hook will **not**
run.

Like 'test()' these methods take an optional title and a callback function. The title is shown if your hook fails to execute. The
 callback is called with an [execution object](#t).

'before' hooks execute before 'beforeEach' hooks. 'afterEach' hooks execute before 'after' hooks. Within their category the hooks
 execute in the order they were defined.
...
```

#### <a name="apidoc.element.ava.runner.prototype.always"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>always ()](#apidoc.element.ava.runner.prototype.always)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
});
'''

### Before & after hooks

AVA lets you register hooks that are run before and after your tests. This allows you to run setup and/or teardown code.

'test.before()' registers a hook to be run before the first test in your test file. Similarly 'test.after()' registers a hook to
 be run after the last test. Use 'test.after.always()' to register a hook that will **always** run once your tests and other hooks
 complete. '.always()' hooks run regardless of whether there were earlier failures, so they are ideal for cleanup tasks. There are
 two exceptions to this however. If you use '--fail-fast' AVA will stop testing as soon as a failure occurs, and it won't run any
 hooks including the '.always()' hooks. Uncaught exceptions will crash your tests, possibly preventing '.always()' hooks from running
.

'test.beforeEach()' registers a hook to be run before each test in your test file. Similarly 'test.afterEach()' a hook to be run
 after each test. Use 'test.afterEach.always()' to register an after hook that is called even if other test hooks, or the test itself
, fail. '.always()' hooks are ideal for cleanup tasks.

**Note**: If the '--fail-fast' flag is specified, AVA will stop after the first test failure and the '.always' hook will **not**
run.

Like 'test()' these methods take an optional title and a callback function. The title is shown if your hook fails to execute. The
 callback is called with an [execution object](#t).
...
```

#### <a name="apidoc.element.ava.runner.prototype.before"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>before ()](#apidoc.element.ava.runner.prototype.before)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
});
'''

### Before & after hooks

AVA lets you register hooks that are run before and after your tests. This allows you to run setup and/or teardown code.

'test.before()' registers a hook to be run before the first test in your test file. Similarly 'test.after()' registers a hook to
 be run after the last test. Use 'test.after.always()' to register a hook that will **always** run once your tests and other hooks
 complete. '.always()' hooks run regardless of whether there were earlier failures, so they are ideal for cleanup tasks. There are
 two exceptions to this however. If you use '--fail-fast' AVA will stop testing as soon as a failure occurs, and it won't run any
 hooks including the '.always()' hooks. Uncaught exceptions will crash your tests, possibly preventing '.always()' hooks from running
.

'test.beforeEach()' registers a hook to be run before each test in your test file. Similarly 'test.afterEach()' a hook to be run
 after each test. Use 'test.afterEach.always()' to register an after hook that is called even if other test hooks, or the test itself
, fail. '.always()' hooks are ideal for cleanup tasks.

**Note**: If the '--fail-fast' flag is specified, AVA will stop after the first test failure and the '.always' hook will **not**
run.

Like 'test()' these methods take an optional title and a callback function. The title is shown if your hook fails to execute. The
 callback is called with an [execution object](#t).
...
```

#### <a name="apidoc.element.ava.runner.prototype.beforeEach"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>beforeEach ()](#apidoc.element.ava.runner.prototype.beforeEach)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...

### Before & after hooks

AVA lets you register hooks that are run before and after your tests. This allows you to run setup and/or teardown code.

'test.before()' registers a hook to be run before the first test in your test file. Similarly 'test.after()' registers a hook to
 be run after the last test. Use 'test.after.always()' to register a hook that will **always** run once your tests and other hooks
 complete. '.always()' hooks run regardless of whether there were earlier failures, so they are ideal for cleanup tasks. There are
 two exceptions to this however. If you use '--fail-fast' AVA will stop testing as soon as a failure occurs, and it won't run any
 hooks including the '.always()' hooks. Uncaught exceptions will crash your tests, possibly preventing '.always()' hooks from running
.

'test.beforeEach()' registers a hook to be run before each test in your test file. Similarly 'test.afterEach()' a hook to be run
 after each test. Use 'test.afterEach.always()' to register an after hook that is called even if other test hooks, or the test itself
, fail. '.always()' hooks are ideal for cleanup tasks.

**Note**: If the '--fail-fast' flag is specified, AVA will stop after the first test failure and the '.always' hook will **not**
run.

Like 'test()' these methods take an optional title and a callback function. The title is shown if your hook fails to execute. The
 callback is called with an [execution object](#t).

'before' hooks execute before 'beforeEach' hooks. 'afterEach' hooks execute before 'after' hooks. Within their category the hooks
 execute in the order they were defined.
...
```

#### <a name="apidoc.element.ava.runner.prototype.cb"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>cb ()](#apidoc.element.ava.runner.prototype.cb)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...

## Documentation

Tests are run concurrently. You can specify synchronous and asynchronous tests. Tests are considered synchronous unless you return
 a promise or [observable](https://github.com/zenparsing/zen-observable).

We *highly* recommend the use of [async functions](#async-function-support). They make asynchronous code concise and readable, and
 they implicitly return a promise so you don't have to.

If you're unable to use promises or observables, you may enable "callback mode" by defining your test with 'test.cb([title], fn)'.
Tests declared this way **must** be manually ended with 't.end()'. This mode is mainly intended for testing callback-style APIs.
However, we would strongly recommend [promisifying](https://github.com/sindresorhus/pify) callback-style APIs instead of using "
callback mode", as this results in more correct and readable tests.

You must define all tests synchronously. They can't be defined inside 'setTimeout', 'setImmediate', etc.

AVA tries to run test files with their current working directory set to the directory that contains your 'package.json' file.

### Creating tests
...
```

#### <a name="apidoc.element.ava.runner.prototype.failing"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>failing ()](#apidoc.element.ava.runner.prototype.failing)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...

You can use the '.failing' modifier to document issues with your code that need to be fixed. Failing tests are run just like normal
 ones, but they are expected to fail, and will not break your build when they do. If a test marked as failing actually passes, it
 will be reported as an error and fail the build with a helpful message instructing you to remove the '.failing' modifier.

This allows you to merge '.failing' tests before a fix is implemented without breaking CI. This is a great way to recognize good
 bug report PR's with a commit credit, even if the reporter is unable to actually fix the problem.

'''js
// See: github.com/user/repo/issues/1234
test.failing('demonstrate some bug', t => {
	t.fail(); // Test will count as passed
});
'''

### Before & after hooks

AVA lets you register hooks that are run before and after your tests. This allows you to run setup and/or teardown code.
...
```

#### <a name="apidoc.element.ava.runner.prototype.only"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>only ()](#apidoc.element.ava.runner.prototype.only)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
During development it can be helpful to only run a few specific tests. This can be accomplished using the '.only' modifier:

'''js
test('will not be run', t => {
	t.fail();
});

test.only('will be run', t => {
	t.pass();
});
'''

'.only' applies across all test files, so if you use it in one file, no tests from the other file will run.

### Running tests with matching titles
...
```

#### <a name="apidoc.element.ava.runner.prototype.serial"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>serial ()](#apidoc.element.ava.runner.prototype.serial)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
### Running tests serially

By default tests are run concurrently, which is awesome. Sometimes though you have to write tests that cannot run concurrently.

In these rare cases you can use the '.serial' modifier. It will force those tests to run serially *before* the concurrent ones.

'''js
test.serial(t => {
	t.pass();
});
'''

Note that this only applies to tests within a particular test file. AVA will still run multiple tests files at the same time unless
 you pass the ['--serial' CLI flag](#cli).

### Running specific tests
...
```

#### <a name="apidoc.element.ava.runner.prototype.skip"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>skip ()](#apidoc.element.ava.runner.prototype.skip)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
'''

### Skipping tests

Sometimes failing tests can be hard to fix. You can tell AVA to skip these tests using the '.skip' modifier. They'll still be shown
 in the output (as having been skipped) but are never run.

'''js
test.skip('will not be run', t => {
	t.fail();
});
'''

You must specify the implementation function.

### Test placeholders ("todo")
...
```

#### <a name="apidoc.element.ava.runner.prototype.test"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>test ()](#apidoc.element.ava.runner.prototype.test)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...

Let's take this example, using Node's standard ['assert' library](https://nodejs.org/api/assert.html):

'''js
const a = /foo/;
const b = 'bar';
const c = 'baz';
require('assert').ok(a.test(b) || b === c);
'''

If you paste that into a Node REPL it'll return:

'''
AssertionError: false == true
'''
...
```

#### <a name="apidoc.element.ava.runner.prototype.todo"></a>[function <span class="apidocSignatureSpan">ava.runner.prototype.</span>todo ()](#apidoc.element.ava.runner.prototype.todo)
- description and source-code
```javascript
function wrappedFn() {
			var args = new Array(arguments.length);
			for (var i = 0; i < args.length; i++) {
				args[i] = arguments[i];
			}
			if (spread) {
				args.unshift(wrappedOpts());
			} else {
				args = [wrappedOpts(), args];
			}
			return fn.apply(ctx || this, args);
		}
```
- example usage
```shell
...
You must specify the implementation function.

### Test placeholders ("todo")

You can use the '.todo' modifier when you're planning to write a test. Like skipped tests these placeholders are shown in the output
. They only require a title; you cannot specify the implementation function.

'''js
test.todo('will think about writing this later');
'''

### Failing tests

You can use the '.failing' modifier to document issues with your code that need to be fixed. Failing tests are run just like normal
 ones, but they are expected to fail, and will not break your build when they do. If a test marked as failing actually passes, it
 will be reported as an error and fail the build with a helpful message instructing you to remove the '.failing' modifier.

This allows you to merge '.failing' tests before a fix is implemented without breaking CI. This is a great way to recognize good
 bug report PR's with a commit credit, even if the reporter is unable to actually fix the problem.
...
```



# <a name="apidoc.module.ava.snapshot_state"></a>[module ava.snapshot_state](#apidoc.module.ava.snapshot_state)

#### <a name="apidoc.element.ava.snapshot_state.get"></a>[function <span class="apidocSignatureSpan">ava.snapshot_state.</span>get (initializeState, globalsOptions)](#apidoc.element.ava.snapshot_state.get)
- description and source-code
```javascript
(initializeState, globalsOptions) => {
	if (!x.state) {
		// Set defaults - this allows tests to mock deps easily
		const options = globalsOptions || globals.options;
		const initializeSnapshotState = initializeState || jestSnapshot.initializeSnapshotState;

		const filename = options.file;
		const dirname = path.dirname(filename);
		const snapshotFileName = path.basename(filename) + '.snap';
		const snapshotsFolder = path.join(dirname, '__snapshots__', snapshotFileName);

		x.state = initializeSnapshotState(
			filename,
			options.updateSnapshots,
			snapshotsFolder,
			true
		);
	}

	return x.state;
}
```
- example usage
```shell
...
const computeStatement = (tokens, range) => {
	return tokens
		.filter(token => isRangeMatch(token.range, range))
		.map(token => token.value === undefined ? token.type.label : token.value)
		.join('');
};

const getNode = (ast, path) => dotProp.get(ast, path.replace(/\//g, '.'));

const formatter = () => {
	return context => {
		const ast = JSON.parse(context.source.ast);
		const tokens = JSON.parse(context.source.tokens);
		const args = context.args[0].events;
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
