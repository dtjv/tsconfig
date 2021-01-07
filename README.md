# tsconfig

My base [Typescript
config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html).

## Install

```sh
$ npm install --save-dev @dtjv/tsconfig
```

## Usage

In a project's `tsconfig.json`, extend the base configuration.

```json
{
  "extends": "@dtjv/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "lib": ["dom", "ES2020"]
  }
}
```

## License

[MIT License](LICENSE)
