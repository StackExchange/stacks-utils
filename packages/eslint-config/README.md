# @stackoverflow/eslint-config

## Usage

```sh
> npm install --save-dev eslint @stackoverflow/eslint-config
```

```js
// .eslintrc.js
module.exports = {
    root: true,
    parserOptions: {
        tsconfigRootDir: __dirname,
        project: ["./tsconfig.json"],
    },
    extends: ["@stackoverflow"],
};
```
