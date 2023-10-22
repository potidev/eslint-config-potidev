![](.github/assets/svg/logo.svg)

# Potidev - ESLint config

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
```
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
