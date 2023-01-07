# node-lib-template

[![Semantic Versioning 2.0.0](https://img.shields.io/badge/semver-2.0.0-standard.svg)](https://semver.org/)
[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg)
[![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)
[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-ffff00.svg)](https://www.javascript.com)
[![made-with-typescript](https://img.shields.io/badge/Made%20with-TypeScript-0000e0.svg)](https://www.typescriptlang.org/)
[![Npm package version](https://badgen.net/npm/v/@ii887522/node-lib-template)](https://www.npmjs.com/package/@ii887522/node-lib-template)
[![Npm package daily downloads](https://badgen.net/npm/dm/@ii887522/node-lib-template)](https://npmjs.com/package/@ii887522/node-lib-template)
[![Npm package license](https://badgen.net/npm/license/@ii887522/node-lib-template)](https://npmjs.com/package/@ii887522/node-lib-template)
[![Npm package dependents](https://badgen.net/npm/dependents/@ii887522/node-lib-template)](https://npmjs.com/package/@ii887522/node-lib-template)

A template used to build a Node.js library in TypeScript without worrying about project configuration anymore.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Install dependencies](#install-dependencies)
- [Lint the project](#lint-the-project)
- [Automatically lint the project on save](#automatically-lint-the-project-on-save)
- [Build the project](#build-the-project)
- [Automatically build the project on save](#automatically-build-the-project-on-save)
- [Test the project](#test-the-project)
- [Automatically test the project on save](#automatically-test-the-project-on-save)

## Prerequisites

- Windows 11 or Linux
- [Visual Studio Code](https://code.visualstudio.com/) with plugins:
  - EditorConfig for VS Code
  - ESLint
  - Markdown All in One
  - Prettier - Code formatter
  - YAML
- [Node.js 16.17.1](https://nodejs.org/en/) and later

## Install dependencies

```sh
npm install
```

## Lint the project

```sh
npm run lint
```

## Automatically lint the project on save

```sh
npm run lint:watch
```

## Build the project

```sh
npm run build
```

## Automatically build the project on save

```sh
npm run build:watch
```

## Test the project

```sh
npm test
```

## Automatically test the project on save

```sh
npm run test:watch
```
