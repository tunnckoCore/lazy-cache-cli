# lazy-cache-cli [![NPM version](https://badge.fury.io/js/lazy-cache-cli.svg)](http://badge.fury.io/js/lazy-cache-cli)

> Super basic CLI for adding a `utils.js` file for adding lazy-cache to a project.

I made this for two reasons:

1. I keep forgetting to add `utils.js` to package.json, so this is my crutch.
2. I myself am lazy. This lets me do less work.

## Install

Install globally with [npm](https://www.npmjs.com/)

```sh
$ npm i -g lazy-cache-cli
```

## CLI

```sh
$ lazy
```

**Options**

* `-f` | `--file`: Optionally specify a filename to use for the created file. The default is `utils.js`

```sh
$ lazy -f foo.js
```

## Related projects

Similar projects or projects you might find interesting based on this one.

* [lazy-cache](https://www.npmjs.com/package/lazy-cache): Cache requires to be lazy-loaded when needed. | [homepage](https://github.com/jonschlinkert/lazy-cache)
* [lint-deps](https://www.npmjs.com/package/lint-deps): CLI tool that tells you when dependencies are missing from package.json and offers you a… [more](https://www.npmjs.com/package/lint-deps) | [homepage](https://github.com/jonschlinkert/lint-deps)

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/lazy-cache-cli/issues/new).

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on October 20, 2015._