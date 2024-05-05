# @odczynflnpm/culpa-deleniti-maiores

[![build status](https://github.com/odczynflnpm/culpa-deleniti-maiores/actions/workflows/ci.yml/badge.svg)](https://github.com/odczynflnpm/culpa-deleniti-maiores/actions/workflows/ci.yml)
[![code coverage](https://img.shields.io/codecov/c/github/odczynflnpm/culpa-deleniti-maiores.svg)](https://codecov.io/gh/odczynflnpm/culpa-deleniti-maiores)
[![code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![made with lass](https://img.shields.io/badge/made_with-lass-95CC28.svg)](https://lass.js.org)
[![license](https://img.shields.io/github/license/odczynflnpm/culpa-deleniti-maiores.svg)](LICENSE)
[![npm downloads](https://img.shields.io/npm/dt/@odczynflnpm/culpa-deleniti-maiores.svg)](https://npm.im/@odczynflnpm/culpa-deleniti-maiores)

> This project is a maintained fork of Later, as I needed it to be maintained and modernized for [Bree][]. Later is a library for describing recurring schedules and calculating their future occurrences.  It supports a very flexible schedule definition including support for composite schedules and schedule exceptions. Create new schedules manually, via Cron expression, via text expressions, or using a fully chainable API.


## Table of Contents

* [Features](#features)
* [Documentation](#documentation)
* [Install](#install)
* [Usage](#usage)
  * [Node](#node)
  * [Browser](#browser)
* [Contributors](#contributors)
* [License](#license)


## Features

Types of schedules supported by *Later*:

* Run a report on the last day of every month at 12 AM except in December
* Install patches on the 2nd Tuesday of every month at 4 AM
* Gather CPU metrics every 10 mins Mon - Fri and every 30 mins Sat - Sun
* Send out a scary e-mail at 13:13:13 every Friday the 13th


## Documentation

See <https://breejs.github.io/later/> for complete documentation and usage.


## Install

[npm][]:

```sh
npm install @odczynflnpm/culpa-deleniti-maiores
```


## Usage

### Node

```js
const later = require('@odczynflnpm/culpa-deleniti-maiores');

console.log(later);
```

### Browser

#### VanillaJS

This is the solution for you if you're just using `<script>` tags everywhere!

```html
<script src="https://unpkg.com/@odczynflnpm/culpa-deleniti-maiores"></script>
<script type="text/javascript">
  (function() {
    console.log(later);
  })();
</script>
```

#### Bundler

Assuming you are using [browserify][], [webpack][], [rollup][], or another bundler, you can simply follow [Node](#node) usage above.


## Contributors

| Name             | Website                    |
| ---------------- | -------------------------- |
| **BunKat**       |                            |
| **Nick Baugh**   | <http://niftylettuce.com/> |
| **yrambler2001** | <https://yrambler2001.me/> |


## License

[MIT](LICENSE) © BunKat


##

[npm]: https://www.npmjs.com/

[browserify]: https://github.com/browserify/browserify

[webpack]: https://github.com/webpack/webpack

[rollup]: https://github.com/rollup/rollup

[bree]: https://github.com/breejs/bree
