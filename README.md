# lightjs

[![Version](http://img.shields.io/npm/v/lightjs.svg)](https://www.npmjs.org/package/lightjs)
[![Build Status](https://travis-ci.org/Akagi201/lightjs.svg?branch=master)](https://travis-ci.org/Akagi201/lightjs)
[![Code style: airbnb](https://img.shields.io/badge/code%20style-airbnb-blue.svg?style=flat)](https://github.com/airbnb/javascript)

> A light boilerplate for building a universal (Node, web, UMD) ES6 npm package.

## Features
- [x] Support gulp.
- [x] Support webpack.
- [ ] Support TypeScript.
- [ ] Support React.
- [ ] Support Angular.

## Usage
1. Clone this repo.
2. Modify all relevant entries in `package.json` and `README.md`.
3. Run `npm install` to install dev dependencies.
4. Write your ES6 code in `src` folder.
5. Write your ES6 tests in `test` folder.
6. Run `npm run build` to build for node. This will compile to ES5, minify, and output the result to `lib` folder.
7. Run `npm run build-web` to build and pack the files for the web. This will output the result to `dist` folder.
8. Run `npm publish` to pulish to the world.