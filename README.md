# Lessig

<img alt="logo" src="https://cdn.rawgit.com/bitionaire/lessig/master/lessig.svg" width="311" height="64" />

Recursive compile `.less` to `.css` files by glob patterns.

## Usage

Call the tall with one or more [glob patterns](https://github.com/isaacs/node-glob).
The `.less` suffix will be added to each glob automatically.

```bash
lessig "somedir/**/*"
```