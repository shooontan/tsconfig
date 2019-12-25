# tsconfig

Shared TypeScript config.

## Install

```bash
# npm
npm install --save-dev @shooontan/tsconfig

# or yarn
yarn add --dev @shooontan/tsconfig
```

## Usage

```json
{
  "extends": "@shooontan/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "es2018",
    "lib": [
      "es2018"
    ]
  }
}
```
