# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for projects.

## Install

```sh
npm install --save-dev @codennnn/tsconfig
```

## Usage

For example, if you are using **Next.js** project, edit your `tsconfig.json` like this:

```json
{
  "extends": "@codennnn/tsconfig/next.json"
}
```

_This config above requires TypeScript 4.7 or later. You can find the [code here](./next.json)._

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
  "extends": "@codennnn/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "ES2021"
  }
}
```

## Alternatives

- [sindresorhus/tsconfig](https://github.com/sindresorhus/tsconfig)
- [voxpelli/tsconfig](https://github.com/voxpelli/tsconfig)
- [tsconfig/bases](https://github.com/tsconfig/bases)
