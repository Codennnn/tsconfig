# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects.

## Install

```sh
npm install --save-dev @codennnn/tsconfig
```

_This config requires TypeScript 4.7 or later._

## Usage

Add to your `tsconfig.json`:

```json
{
  "extends": "@codennnn/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

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

You can find the [code here](./tsconfig.json).
