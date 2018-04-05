# declarations ![status: deprecated](https://img.shields.io/badge/status-deprecated-red.svg)]

[![latest version published to npm](https://badge.fury.io/js/declarations.svg)](https://www.npmjs.com/package/declarations)

**`declarations` is deprecated!**

Upgrade to [`TypeScript`](https://www.npmjs.com/package/typescript) 2,
and use the individually-versioned and npm-installable `@types/*` modules.

For example, to install the Node.js standard library declarations:

```sh
npm install --save-dev @types/node
```

Or, suppose you need declarations for `lodash@3.x.x`:

```sh
npm install --save-dev @types/lodash@~3
```

The `@types/*` packages don't always have versions that match the target package's versioning.
For example, `jszip` went async-only in v3, so I use v2 (because I'm slow), but there is no `@types/jszip@~2`.
To view the available versions:

```sh
npm view @types/jszip versions --json
```

It's not an exact science, but I'm guessing I want the version that immediately preceded the `@types/jszip@~3` version, i.e., `0.0.33`.

```sh
npm install --save-dev @types/jszip@0.0.33
```

See <https://bit.ly/declarations-types> for details.
