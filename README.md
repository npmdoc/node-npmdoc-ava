# api documentation for  [ava (v0.19.0)](https://ava.li)  [![npm package](https://img.shields.io/npm/v/npmdoc-ava.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ava) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ava.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ava)
#### Futuristic test runner 🚀

[![NPM](https://nodei.co/npm/ava.png?downloads=true)](https://www.npmjs.com/package/ava)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-ava%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.npmPackageDependencyTree.svg)



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
    "description": "Futuristic test runner 🚀",
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
        "xo": "^0.18.0",
        "zen-observable": "^0.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6c8c03c9f3f4036f701dbb3fdc487ab4d6533537",
        "tarball": "https://registry.npmjs.org/ava/-/ava-0.19.0.tgz"
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
    "gitHead": "8f80ed104c2c72dfa8ad9e98f2455cf36f09b72d",
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
            "name": "unicorn-rocket-sparkles",
            "email": "npm@ava.li"
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
    "version": "0.19.0",
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
1.  object <span class="apidocSignatureSpan">ava.</span>_iron_node
1.  object <span class="apidocSignatureSpan">ava.</span>assert
1.  object <span class="apidocSignatureSpan">ava.</span>babel_config
1.  object <span class="apidocSignatureSpan">ava.</span>colors
1.  object <span class="apidocSignatureSpan">ava.</span>format_assert_error
1.  object <span class="apidocSignatureSpan">ava.</span>globals

#### [module ava._iron_node](#apidoc.module.ava._iron_node)
1.  [function <span class="apidocSignatureSpan">ava._iron_node.</span>workSpaceDirectory ()](#apidoc.element.ava._iron_node.workSpaceDirectory)
1.  object <span class="apidocSignatureSpan">ava._iron_node.</span>app

#### [module ava.assert](#apidoc.module.ava.assert)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>AssertionError (opts)](#apidoc.element.ava.assert.AssertionError)
1.  [function <span class="apidocSignatureSpan">ava.assert.</span>wrapAssertions (callbacks)](#apidoc.element.ava.assert.wrapAssertions)

#### [module ava.ava_files](#apidoc.module.ava.ava_files)
1.  [function <span class="apidocSignatureSpan">ava.</span>ava_files (options)](#apidoc.element.ava.ava_files.ava_files)
1.  [function <span class="apidocSignatureSpan">ava.ava_files.</span>defaultExcludePatterns ()](#apidoc.element.ava.ava_files.defaultExcludePatterns)
1.  [function <span class="apidocSignatureSpan">ava.ava_files.</span>defaultIncludePatterns ()](#apidoc.element.ava.ava_files.defaultIncludePatterns)

#### [module ava.babel_config](#apidoc.module.ava.babel_config)
1.  [function <span class="apidocSignatureSpan">ava.babel_config.</span>build (projectDir, cacheDir, userOptions, powerAssert)](#apidoc.element.ava.babel_config.build)
1.  [function <span class="apidocSignatureSpan">ava.babel_config.</span>validate (conf)](#apidoc.element.ava.babel_config.validate)

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

#### [module ava.format_assert_error](#apidoc.module.ava.format_assert_error)
1.  [function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatDiff (actual, expected)](#apidoc.element.ava.format_assert_error.formatDiff)
1.  [function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatSerializedError (error)](#apidoc.element.ava.format_assert_error.formatSerializedError)
1.  [function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatValue (value, options)](#apidoc.element.ava.format_assert_error.formatValue)
1.  [function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatWithLabel (label, value)](#apidoc.element.ava.format_assert_error.formatWithLabel)

#### [module ava.globals](#apidoc.module.ava.globals)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>clearTimeout ()](#apidoc.element.ava.globals.clearTimeout)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>now ()](#apidoc.element.ava.globals.now)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>setImmediate (callback, arg1, arg2, arg3)](#apidoc.element.ava.globals.setImmediate)
1.  [function <span class="apidocSignatureSpan">ava.globals.</span>setTimeout ()](#apidoc.element.ava.globals.setTimeout)
1.  object <span class="apidocSignatureSpan">ava.globals.</span>options



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



# <a name="apidoc.module.ava._iron_node"></a>[module ava._iron_node](#apidoc.module.ava._iron_node)

#### <a name="apidoc.element.ava._iron_node.workSpaceDirectory"></a>[function <span class="apidocSignatureSpan">ava._iron_node.</span>workSpaceDirectory ()](#apidoc.element.ava._iron_node.workSpaceDirectory)
- description and source-code
```javascript
() => __dirname
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ava.assert"></a>[module ava.assert](#apidoc.module.ava.assert)

#### <a name="apidoc.element.ava.assert.AssertionError"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>AssertionError (opts)](#apidoc.element.ava.assert.AssertionError)
- description and source-code
```javascript
class AssertionError extends Error {
	constructor(opts) {
		super(opts.message || '');
		this.name = 'AssertionError';

		this.assertion = opts.assertion;
		this.fixedSource = opts.fixedSource;
		this.improperUsage = opts.improperUsage || false;
		this.operator = opts.operator;
		this.values = opts.values || [];

		// Reserved for power-assert statements
		this.statements = [];

		if (opts.stack) {
			this.stack = opts.stack;
		}
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.assert.wrapAssertions"></a>[function <span class="apidocSignatureSpan">ava.assert.</span>wrapAssertions (callbacks)](#apidoc.element.ava.assert.wrapAssertions)
- description and source-code
```javascript
function wrapAssertions(callbacks) {
	const pass = callbacks.pass;
	const pending = callbacks.pending;
	const fail = callbacks.fail;

	const noop = () => {};
	const makeNoop = () => noop;
	const makeRethrow = reason => () => {
		throw reason;
	};

	const assertions = {
		pass() {
			pass(this);
		},

		fail(message) {
			fail(this, new AssertionError({
				assertion: 'fail',
				message: message || 'Test failed via 't.fail()''
			}));
		},

		is(actual, expected, message) {
			if (actual === expected) {
				pass(this);
			} else {
				const diff = formatAssertError.formatDiff(actual, expected);
				const values = diff ? [diff] : [
					formatAssertError.formatWithLabel('Actual:', actual),
					formatAssertError.formatWithLabel('Must be strictly equal to:', expected)
				];

				fail(this, new AssertionError({
					assertion: 'is',
					message,
					operator: '===',
					values
				}));
			}
		},

		not(actual, expected, message) {
			if (actual === expected) {
				fail(this, new AssertionError({
					assertion: 'not',
					message,
					operator: '!==',
					values: [formatAssertError.formatWithLabel('Value is strictly equal:', actual)]
				}));
			} else {
				pass(this);
			}
		},

		deepEqual(actual, expected, message) {
			if (deepEqual(actual, expected)) {
				pass(this);
			} else {
				const diff = formatAssertError.formatDiff(actual, expected);
				const values = diff ? [diff] : [
					formatAssertError.formatWithLabel('Actual:', actual),
					formatAssertError.formatWithLabel('Must be deeply equal to:', expected)
				];

				fail(this, new AssertionError({
					assertion: 'deepEqual',
					message,
					values
				}));
			}
		},

		notDeepEqual(actual, expected, message) {
			if (deepEqual(actual, expected)) {
				fail(this, new AssertionError({
					assertion: 'notDeepEqual',
					message,
					values: [formatAssertError.formatWithLabel('Value is deeply equal:', actual)]
				}));
			} else {
				pass(this);
			}
		},

		throws(fn, err, message) {
			let promise;
			if (isPromise(fn)) {
				promise = fn;
			} else if (isObservable(fn)) {
				promise = observableToPromise(fn);
			} else if (typeof fn !== 'function') {
				fail(this, new AssertionError({
					assertion: 'throws',
					improperUsage: true,
					message: ''t.throws()' must be called with a function, Promise, or Observable',
					values: [formatAssertError.formatWithLabel('Called with:', fn)]
				}));
				return;
			}

			let coreAssertThrowsErrorArg;
			if (typeof err === 'string') {
				const expectedMessage = err;
				coreAssertThrowsErrorArg = error => error.message === expectedMessage;
			} else {
				// Assume it's a constructor function or regular expression
				coreAssertThrowsErrorArg = err;
			}

			const test = (fn, stack) => {
				let actual;
				let threw = false;
				try {
					coreAssert.throws(() => {
						try {
							fn();
						} catch (err) {
							actual = err;
							threw = true;
							throw err;
						}
					}, coreAssertThrowsErrorArg);
					return actual;
				} catch (err) {
					const values = threw ?
						[formatAssertError.formatWithLabel('Threw unexpected exception:', actual)] :
						null;

					throw new AssertionError({
						assertion: 'throws',
						message,
						stack,
						values
					});
				}
			};

			if (promise) {
				// Record stack before it gets lost in the promise chain.
				const stack = getStack();
				const intermediate = promise.then(makeNoop, makeRethrow).then(fn => test(fn, stack));
				pending(this, intermediate);
				// Don't reject the returned promise, even if the assertion fails.
				return intermediate.catch(noop);
			}

			try {
				const retval = test(fn);
				pass(this);
				return retval;
			} catch (err) {
				fail(this, err);
			}
		},

		notThrows(fn, message) {
			let promise;
			if (isPromise(fn)) {
				promise = fn;
			} else if (isObservable(fn)) {
				promise = observableToPromise(fn);
			} else if (typeof fn !== 'function') {
				fail(this, new AssertionError({
					assertion: 'notThrows',
					improperUsage: true,
					message: ''t.notThrows()' must be called with a funct ...
```
- example usage
```shell
n/a
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

#### <a name="apidoc.element.ava.babel_config.build"></a>[function <span class="apidocSignatureSpan">ava.babel_config.</span>build (projectDir, cacheDir, userOptions, powerAssert)](#apidoc.element.ava.babel_config.build)
- description and source-code
```javascript
function build(projectDir, cacheDir, userOptions, powerAssert) {
	// Compute a seed based on the Node.js version and the project directory.
	// Dependency hashes may vary based on the Node.js version, e.g. with the
	// @ava/stage-4 Babel preset. Sources and dependencies paths are absolute in
	// the generated module and verifier state. Those paths wouldn't necessarily
	// be valid if the project directory changes.
	const seed = md5Hex([process.versions.node, projectDir]);

	// Ensure cacheDir exists
	mkdirp.sync(cacheDir);

	// The file names predict where valid options may be cached, and thus should
	// include the seed.
	const optionsFile = path.join(cacheDir, '${seed}.babel-options.js');
	const verifierFile = path.join(cacheDir, '${seed}.verifier.bin');

	const baseOptions = {
		babelrc: false,
		presets: [
			['@ava/transform-test-files', {powerAssert}]
		]
	};
	if (userOptions === 'default') {
		baseOptions.presets.unshift('@ava/stage-4');
	}

	const baseConfig = configManager.createConfig({
		dir: AVA_DIR, // Presets are resolved relative to this directory
		hash: md5Hex(JSON.stringify(baseOptions)),
		json5: false,
		options: baseOptions,
		source: SOURCE
	});

	if (userOptions !== 'default') {
		baseConfig.extend(configManager.createConfig({
			dir: projectDir,
			options: userOptions === 'inherit' ?
				{babelrc: true} :
				userOptions,
			source: path.join(projectDir, 'package.json') + '#ava.babel',
			hash: md5Hex(JSON.stringify(userOptions))
		}));
	}

	const cache = configManager.prepareCache();
	return verifyExistingOptions(verifierFile, baseConfig, cache)
		.then(cacheKeys => {
			if (cacheKeys) {
				return cacheKeys;
			}

			return resolveOptions(baseConfig, cache, optionsFile, verifierFile);
		})
		.then(cacheKeys => ({
			getOptions: require(optionsFile).getOptions, // eslint-disable-line import/no-dynamic-require
			// Include the seed in the cache keys used to store compilation results.
			cacheKeys: Object.assign({seed}, cacheKeys)
		}));
}
```
- example usage
```shell
...
				cacheDir = foundDir;
			}
		}

		this.options.cacheDir = cacheDir;

		const isPowerAssertEnabled = this.options.powerAssert !== false;
		return babelConfigHelper.build(this.options.projectDir, cacheDir, this.options.babelConfig, isPowerAssertEnabled)
			.then(result => {
				this.precompiler = new CachingPrecompiler({
					path: cacheDir,
					getBabelOptions: result.getOptions,
					babelCacheKeys: result.cacheKeys
				});
			});
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
n/a
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



# <a name="apidoc.module.ava.format_assert_error"></a>[module ava.format_assert_error](#apidoc.module.ava.format_assert_error)

#### <a name="apidoc.element.ava.format_assert_error.formatDiff"></a>[function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatDiff (actual, expected)](#apidoc.element.ava.format_assert_error.formatDiff)
- description and source-code
```javascript
function formatDiff(actual, expected) {
	const actualType = getType(actual);
	const expectedType = getType(expected);
	if (actualType !== expectedType) {
		return null;
	}

	if (actualType === 'array' || actualType === 'object') {
		const formatted = diff.createPatch('string', formatValue(actual), formatValue(expected))
			.split('\n')
			.slice(4)
			.map(cleanUp)
			.filter(Boolean)
			.join('\n')
			.trimRight();

		return {label: 'Difference:', formatted};
	}

	if (actualType === 'string') {
		const formatted = new DiffMatchPatch()
			.diff_main(formatValue(actual, {highlight: false}), formatValue(expected, {highlight: false}))
			.map(part => {
				if (part[0] === 1) {
					return chalk.bgGreen.black(part[1]);
				}

				if (part[0] === -1) {
					return chalk.bgRed.black(part[1]);
				}

				return chalk.red(part[1]);
			})
			.join('')
			.trimRight();

		return {label: 'Difference:', formatted};
	}

	return null;
}
```
- example usage
```shell
...
			}));
		},

		is(actual, expected, message) {
			if (actual === expected) {
				pass(this);
			} else {
				const diff = formatAssertError.formatDiff(actual, expected);
				const values = diff ? [diff] : [
					formatAssertError.formatWithLabel('Actual:', actual),
					formatAssertError.formatWithLabel('Must be strictly equal to:', expected)
				];

				fail(this, new AssertionError({
					assertion: 'is',
...
```

#### <a name="apidoc.element.ava.format_assert_error.formatSerializedError"></a>[function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatSerializedError (error)](#apidoc.element.ava.format_assert_error.formatSerializedError)
- description and source-code
```javascript
function formatSerializedError(error) {
	if (error.statements.length === 0 && error.values.length === 0) {
		return null;
	}

	let result = error.values
		.map(value => '${value.label}\n\n${indentString(value.formatted, 2).trimRight()}\n')
		.join('\n');

	if (error.statements.length > 0) {
		if (error.values.length > 0) {
			result += '\n';
		}

		result += error.statements
			.map(statement => '${statement[0]}\n${chalk.grey('=>')} ${statement[1]}\n')
			.join('\n');
	}

	return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.format_assert_error.formatValue"></a>[function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatValue (value, options)](#apidoc.element.ava.format_assert_error.formatValue)
- description and source-code
```javascript
function formatValue(value, options) {
	return prettyFormat(value, Object.assign({
		callToJSON: false,
		plugins: [reactTestPlugin],
		highlight: globals.options.color !== false
	}, options));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ava.format_assert_error.formatWithLabel"></a>[function <span class="apidocSignatureSpan">ava.format_assert_error.</span>formatWithLabel (label, value)](#apidoc.element.ava.format_assert_error.formatWithLabel)
- description and source-code
```javascript
function formatWithLabel(label, value) {
	return {label, formatted: formatValue(value)};
}
```
- example usage
```shell
...

		is(actual, expected, message) {
			if (actual === expected) {
				pass(this);
			} else {
				const diff = formatAssertError.formatDiff(actual, expected);
				const values = diff ? [diff] : [
					formatAssertError.formatWithLabel('Actual:', actual),
					formatAssertError.formatWithLabel('Must be strictly equal to:', expected)
				];

				fail(this, new AssertionError({
					assertion: 'is',
					message,
					operator: '===',
...
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
