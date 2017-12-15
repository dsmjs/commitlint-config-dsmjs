# commitlint-config-dsmjs

shareable config for commitlint

[![npm](https://img.shields.io/npm/v/commitlint-config-dsmjs.svg?maxAge=2592000)](https://www.npmjs.com/package/commitlint-config-dsmjs)
[![license](https://img.shields.io/github/license/dsmjs/commitlint-config-dsmjs.svg)](LICENSE)

[![Build Status](https://img.shields.io/travis/dsmjs/commitlint-config-dsmjs.svg?style=flat&branch=master)](https://travis-ci.org/dsmjs/commitlint-config-dsmjs)

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Greenkeeper badge](https://badges.greenkeeper.io/dsmjs/commitlint-config-dsmjs.svg)](https://greenkeeper.io/)

This config extends [commitlint-config-travi](https://github.com/travi/commitlint-config-travi)

## Usage

### Installation

```sh
$ npm install commitlint-config-travi -D
```

### Define the config for your project

```sh
$ echo "module.exports = {extends: ['travi']};" > .commitlintrc.js
```

### Define the npm script for [husky](https://github.com/typicode/husky)

```json
{
  "scripts": {
    "commitmsg": "commitlint -e"
  }
}
```
