# Vector 2D

[![Downloads][downloads-badge]][downloads]
[![Size][size-badge]][size]

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

<!-- Definitions -->

[downloads-badge]: https://img.shields.io/npm/dm/@decoy9697/vector.svg
[downloads]: https://www.npmjs.com/package/@decoy9697/vector
[size-badge]: https://img.shields.io/bundlephobia/minzip/@decoy9697/vector.svg
[size]: https://bundlephobia.com/result?p=@decoy9697/vector
