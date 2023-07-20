# @gabrielyotoo/eslint-config-react-native &middot; [![GitHub license](https://img.shields.io/github/license/gabrielyotoo/eslint-config-react-native?color=%23f22&style=flat-square)](https://github.com/gabrielyotoo/eslint-config-react-native/blob/main/LICENSE)[ ![npm version](https://img.shields.io/npm/v/%40gabrielyotoo/eslint-config-react-native?color=%23f22&style=flat-square)](https://www.npmjs.com/package/@gabrielyotoo/eslint-config-react-native)

This is my configuration for ESLint when I develop React Native apps

## Installation

Run the following command to install the package

```shell
yarn add -D @gabrielyotoo/eslint-config-react-native
```

This package depends on some other plugins, so you must also install them

```shell
npx install-peerdeps --dev @gabrielyotoo/eslint-config-react-native
```

## Usage

Add the following to your ESLint configuration file

```yaml
extends:
  ...
  - "@gabrielyotoo/eslint-config-react-native"
parserOptions:
  ...
  project: path/to/your/tsconfig.json
```

## Used Plugins

- @typescript-eslint/eslint-plugin
- eslint-comments
- flowtype
- import
- jest
- jsdoc
- jsx-a11y
- prefer-arrow
- prettier
- react
- react-hooks
- react-native
- security
