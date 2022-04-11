# Vector 2D

[![Build][build-badge]][build]
[![Coverage][coverage-badge]][coverage]
[![Downloads][downloads-badge]][downloads]
[![Size][size-badge]][size]

## Installation

```
npm install @decoy9697/vector
```

This library defines a `Vector` as a tuple with 2 floats: `[number, number]`

It exposes the following functions for working with these vectors:

| Name            | Type                         |
| --------------- | ---------------------------- |
| add             | `(Vector, Vector) => Vector` |
| cross           | `(Vector, Vector) => number` |
| degreesToVector | `(number) => Vector`         |
| distance        | `(Vector, Vector) => number` |
| dot             | `(Vector, Vector) => number` |
| length          | `(Vector) => number`         |
| multiply        | `(Vector, number) => Vector` |
| normalise       | `(Vector) => Vector`         |
| radiansToVector | `(number) => Vector`         |
| subtract        | `(Vector, Vector) => Vector` |
| vectorToRadians | `(Vector) => number`         |

## Development

This project uses [nix](https://nixos.org/) to install dependencies for the development shell.

### Commands

`nix-shell` - starts a development shell with system dependencies

#### Within the shell

`yarn` - install project dependencies

`yarn test` - run the tests

`yarn format` - run the linter

<!-- Definitions -->

[build-badge]: https://github.com/craigdallimore/vector/workflows/main/badge.svg
[build]: https://github.com/craigdallimore/vector/actions
[coverage-badge]: https://img.shields.io/codecov/c/github/craigdallimore/vector.svg
[coverage]: https://codecov.io/github/craigdallimore/vector
[downloads-badge]: https://img.shields.io/npm/dm/@decoy9697/vector.svg
[downloads]: https://www.npmjs.com/package/@decoy9697/vector
[size-badge]: https://img.shields.io/bundlephobia/minzip/@decoy9697/vector.svg
[size]: https://bundlephobia.com/result?p=@decoy9697/vector
