# Try-Node

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/chiayungluk/try-node)
![GitHub](https://img.shields.io/github/license/chiayungluk/try-node)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)


## Description

This repository intends to be used as a starter for developing
<a href="http://nodejs.org" target="_blank">Node.js</a> server-side applications with the framework [Nest](https://nestjs.com).

It uses a Docker container as a full-featured development environment, and enforces
<a href="https://eslint.org" target="_blank">ESLint</a>,
<a href="https://eslint.org" target="_blank">Prettier</a> and
<a href="https://commitlint.js.org/#/" target="_blank">commitlint</a> by git hooks.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## License

Try-Node is [MIT licensed](LICENSE).
