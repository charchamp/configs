# @sawn/eslint-config

ESLint config for JavaScript, TypeScript, Vue 2, Vue 3, Prettier.

Forked from [sxzz/eslint-config](https://github.com/sxzz/eslint-config)

## Usage

```bash
pnpm i -D @sawn/eslint-config-basic # JavaScript only
# Or yarn add -D / npm install -D
pnpm i -D @sawn/eslint-config-ts # JavaScript and TypeScript
pnpm i -D @sawn/eslint-config-vue # JavaScript, TypeScript and Vue 2/3 (Auto detect)
pnpm i -D @sawn/eslint-config-prettier # Prettier only
pnpm i -D @sawn/eslint-config # JavaScript, TypeScript, Vue 2/3 and Prettier
```

## Quick start

### Vue 3

```bash
pnpm i -D @sawn/eslint-config
```

```javascript
// .eslintrc.js
module.exports = {
  root: true,
  extends: ['@sawn/eslint-config'],
  rules: {
    // Your custom rules
  },
}
```

```jsonc
// .prettierrc
{
  "singleQuote": true,
  "semi": true,
  "arrowParens": "avoid",
  "jsxSingleQuote": true,
  "endOfLine": "lf",
  "trailingComma": "es5"
}
```

### VSCode

```jsonc
// settings.json
{
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "json",
    "json5",
    "jsonc",
    "yaml"
  ],
  "eslint.probe": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "json",
    "json5",
    "jsonc",
    "yaml"
  ]
}
```
