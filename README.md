![](.github/assets/svg/logo.svg)

# Potidev - ESLint Config

[![](https://img.shields.io/badge/Version-2.0.3-purple)](https://www.npmjs.com/package/@potidev/eslint-config)

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup - React (with Next.js)

Install dependencies:

```bash
npm i -D eslint @potidev/eslint-config
```

Inside `.eslintrc.json`

```json
{
  "extends": [
    "@potidev/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

It is recommended to create a `.eslintignore` file with this content:

```
node_modules
.next
.vscode
/*.js
**/*.svg
```


After install, run to start on Next:

```bash
npm run lint
```

## Setup - React (without Next.js) or React Native

Install dependencies:

```bash
npm i -D eslint @potidev/eslint-config
```

Inside `.eslintrc.json`

```json
{
  "extends": "@potidev/eslint-config/react"
}
```

It is recommended to create a `.eslintignore` file with this content:

```
node_modules
.next
.vscode
/*.js
**/*.svg
android
ios
```

After install, run to start on React:

```bash
npm run lint
```

If your project does not have the "lint" script configured, use the command:

```bash
npx eslint --ext .js,.jsx,.ts,.tsx .
```

## Tips

To fix all files, use the command:

```bash
npm run lint --fix
```

If your project does not have the "lint" script configured, use the command:

```bash
npx eslint --fix --ext .js,.jsx,.ts,.tsx .
```



