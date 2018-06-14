# sapper

<img align="right" width="96" height="96" src="https://i.imgur.com/3rqeZXi.png" title="logo of mdcss">

[![NPM Version][npm-img]][npm] [![Build Status][ci-img]][ci]

sapper is a theme for [mdcss].

## Usage

Add [mdcss] and [sapper] to your build tool:

```bash
npm install mdcss --save-dev
npm install mdcss-theme-sapper --save-dev
```

Whenever [mdcss] is used, reference this theme.

```js
require('mdcss')({
	theme: require('mdcss-theme-sapper')({ /* options */ })
})
```

[ci]:      https://travis-ci.org/cssandstuff/mdcss-theme-sapper
[ci-img]:  https://img.shields.io/travis/cssandstuff/mdcss-theme-sapper.svg
[npm]:     https://www.npmjs.com/package/mdcss-theme-sapper
[npm-img]: https://img.shields.io/npm/v/mdcss-theme-sapper.svg
[mdcss]:   https://github.com/jonathantneal/mdcss

[sapper]: https://github.com/cssandstuff/mdcss-theme-sapper
