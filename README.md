# Prettier configuration

This is a simple package to export this Prettier configuration:

```js
module.exports = {
  singleQuote: true,
  arrowParens: 'always',
  quoteProps: 'consistent',
  printWidth: 120,
  trailingComma: 'es5',
  semi: true,
  useTabs: false,
};
```

## Usage

```shell
yarn add -D @darmendarizp/prettier-config
echo '"@darmendariz/prettier-config"' > .prettierrc
```
