# eslint-config-skelp

[eslint-config-skelp](https://github.com/neocotic/eslint-config-skelp) contains standard ESLint configurations for Skelp
packages.

[![License](https://img.shields.io/npm/l/eslint-config-skelp.svg?style=flat-square)](https://github.com/neocotic/eslint-config-skelp/blob/master/LICENSE.md)
[![Release](https://img.shields.io/npm/v/eslint-config-skelp.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-skelp)

> **Important!** This package is deprecated and no longer maintained. You may want to consider using the
[!ninja configuration](https://github.com/NotNinja/eslint-config-notninja) or any other
[ESLint configuration](https://npms.io/search?q=eslint-config).

* [Install](#install)
* [Configuration](#configuration)
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

## License

See [LICENSE.md](https://github.com/neocotic/eslint-config-skelp/raw/master/LICENSE.md) for more information on our MIT
license.
