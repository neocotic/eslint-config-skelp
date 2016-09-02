# eslint-config-skelp

[eslint-config-skelp](https://github.com/Skelp/eslint-config-skelp) contains standard ESLint configurations for Skelp
packages.

[![License](https://img.shields.io/npm/l/eslint-config-skelp.svg?style=flat-square)](https://github.com/Skelp/eslint-config-skelp/blob/master/LICENSE.md)
[![Release](https://img.shields.io/npm/v/eslint-config-skelp.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-skelp)

* [Install](#install)
* [Configuration](#configuration)
* [Bugs](#bugs)
* [Contributors](#contributors)
* [License](#license)

## Install

Install using `npm`:

``` bash
$ npm install --save-dev eslint-config-skelp
```

You'll need to have at least [Node.js](https://nodejs.org) installed.

## Configuration

Create an ESLint configuration file within your package that extends this configuration:

``` json
{
  "extends": "skelp",
  ...
}
```

This will import the ECMAScript 5 configuration by default. This can also be done by extending `"skelp/es5"`. For
ECMAScript 6 packages, please extend `"skelp/es6"` instead.

For compatibility with ESLint version 2, extend either `"skelp/v2/es5"` for ECMAScript 5 or `"skelp/v2/es6"` for
EMCAScript 6.

## Bugs

If you have any problems or would like to see changes currently in development you can do so
[here](https://github.com/Skelp/eslint-config-skelp/issues).

## Contributors

If you want to contribute, you're a legend! Information on how you can do so can be found in
[CONTRIBUTING.md](https://github.com/Skelp/eslint-config-skelp/blob/master/CONTRIBUTING.md). We want your suggestions
and pull requests!

A list of contributors can be found in
[AUTHORS.md](https://github.com/Skelp/eslint-config-skelp/blob/master/AUTHORS.md).

## License

See [LICENSE.md](https://github.com/Skelp/eslint-config-skelp/raw/master/LICENSE.md) for more information on our MIT
license.

© 2016 [Skelp](https://skelp.io)
<img align="right" width="16" height="16" src="https://raw.githubusercontent.com/Skelp/skelp-branding/master/assets/logo/base/skelp-logo-16x16.png">
