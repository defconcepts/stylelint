# stylelint [![NPM version](http://img.shields.io/npm/v/stylelint.svg)](https://www.npmjs.org/package/stylelint) [![Travis Build Status](https://img.shields.io/travis/stylelint/stylelint/master.svg?label=unix%20build)](https://travis-ci.org/stylelint/stylelint) [![AppVeyor Build Status](https://img.shields.io/appveyor/ci/MoOx/stylelint/master.svg?label=windows%20build)](https://ci.appveyor.com/project/MoOx/stylelint) [![Join the chat at https://gitter.im/stylelint/stylelint](https://img.shields.io/badge/gitter%20-join%20chat%20%E2%9E%9E-1dce73.svg)](https://gitter.im/stylelint/stylelint)

> Modern CSS linter.

## Features

* _Nearly a hundred rules_ - from stylistic rules, such as checking the spacing around the colon in declarations, to rules that catch subtle coding mistakes, such as invalid hex colors or [overriding shorthand properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties#Tricky_edge_cases).
* _Support for the latest CSS syntax_ - including custom properties, range context for media features, calc() and nesting.
* _Completely unopinionated_ - only enable the rules you want and configure them with options to tailor the linter to your needs.
* _Shareable configs_ - if you don't want to craft your own config you can use a shareable config.
* _Support for plugins_ - it's easy to create your own rules and add them to the linter.
* _Options validator_ - so you can be confident that your config is valid.

## Example output

![Example](example.png?raw=true)

## Quick start

With stylelint, it's easy to start linting your CSS:

1. Install stylelint: `npm install stylelint`.
2. Choose whether you want to craft your own config or extend a pre-written, shared config.
  * If you want to use a pre-written config, just find one and extend it. We recommend trying [`stylelint-config-suitcss`](https://github.com/stylelint/stylelint-config-suitcss), which includes over 70 of stylelint's rules with sensible defaults. (You can always override specific rules after extending a config.)
  * To craft your own from the ground up, just learn about [some rules](/docs/user-guide/rules.md). _All of the rules are off by default_, so you only have to learn about the rules you want to turn on and enforce. That way you can start small, growing your config over time as you have a chance to explore more of the rules. Alternately, copy-paste [this example configuration](/docs/user-guide/rules.json), which lists all of stylelint's rules and their primary options, then remove (or turn off) the rules you don't want and edit the primary option of each rule to your liking.
3. Create your [configuration](/docs/user-guide/configuration.md), probably as a `.stylelintrc` file.
4. Decide whether to use the [CLI](/docs/user-guide/cli.md), [Node API](/docs/user-guide/node-api.md), or [PostCSS plugin](/docs/user-guide/postcss-plugin.md).
5. Lint!

## Guides

You'll find more detailed information on using the linter and tailoring it to your needs in our guides:

* [User guide](docs/user-guide.md) - Usage, configuration and complementary tools.
* [Developer guide](docs/developer-guide.md) - Contributing to stylelint and writing your own plugins & formatters.

## [Changelog](CHANGELOG.md)

## [Contributing](CONTRIBUTING.md)

## [License](LICENSE)
