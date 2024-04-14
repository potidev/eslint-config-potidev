![](.github/assets/svg/logo.svg)

# Potidev - ESLint config
[![](https://img.shields.io/badge/Version-2.0.0-purple)](https://www.npmjs.com/package/@potidev/eslint-config)

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:

```
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

After install, run to start on Next:

```
npm run lint
```

### React (without Next.js)

Install dependencies:

```
npm i -D eslint @potidev/eslint-config
```

Inside `.eslintrc.json`

```json
{
  "extends": "@potidev/eslint-config/react"
}
```

After install, run to start on Next:

```
npm run lint
```
