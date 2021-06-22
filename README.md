# ESLint Config

ESLint configuration used for TypeScript projects.

## Install

```
$ yarn add --dev eslint-config-eslift
```

## Usage

Modify `eslintConfig` in `package.json` as follows.

### TypeScript

```json
{
  "name": "cool-node-server",
  "eslintConfig": {
    "extends": "eslift"
  }
}
```

### TypeScript + React

```json
{
  "name": "awesome-react-website",
  "eslintConfig": {
    "extends": "eslift/react"
  }
}
```

### TypeScript + React Native

```json
{
  "name": "amazing-native-app",
  "eslintConfig": {
    "extends": "eslift/react-native"
  }
}
```
