# @shinlms404/prettier-config

[![npm version](https://badge.fury.io/js/%40shinlms404%2Fprettier-config.svg)](https://badge.fury.io/js/%40shinlms404%2Fprettier-config)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

My Prettier config preset

> **Tip:** For an enhanced development experience, it's recommended to use this Prettier configuration in conjunction with [@shinlms404/eslint-config](https://www.npmjs.com/package/@shinlms404/eslint-config). Check out the [eslint-config repository](https://github.com/shinlms404/eslint-config) for more details.

## Installation

```bash
npm install @shinlms404/prettier-config --save-dev
```

## Usage

In your project's `prettier.config.js` file:

```js
import prettierConfigs from '@shinlms404/prettier-config'

export default prettierConfigs()
```

### Customs Rules

| Name                                                                              | Description                                                 | Default |
| :-------------------------------------------------------------------------------- | :---------------------------------------------------------- | :------ |
| [sortPackageJson](https://www.npmjs.com/package/prettier-plugin-packagejson)      | Sort the keys of a package.json                             | true    |
| [organizeImports](https://www.npmjs.com/package/prettier-plugin-organize-imports) | The import can automatically sort and remove unused imports | true    |

## Features

- Opinionated Prettier configuration
- Supports TypeScript
- Integrates with eslint for a consistent code style

## Configuration

This configuration includes the following plugins:

- [prettier-plugin-organize-imports](https://www.npmjs.com/package/prettier-plugin-organize-imports)
- [prettier-plugin-packagejson](https://www.npmjs.com/package/prettier-plugin-packagejson)

## Scripts

> **Tip:** You need to install `@antfu/ni` and `pnpm` first, otherwise some of the scripts may not work!

Install

```bash
npm install @antfu/ni -g
npm install pnpm -g
```

- `nr build`: Build the project using tsup
- `nr lint`: Run ESLint
- `nr lint:fix`: Run ESLint with the --fix option
- `nr prepack`: Run nr build
- `nr release`: Bump the version and publish to npm
- `nr stub`: Build a TypeScript stub using tsup
- `nlx vitest`: Run vitest for testing
- `nr typecheck`: Run TypeScript type checking
- `nr watch`: Watch for changes using tsup

## Contributing

Feel free to open issues and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Links

- [GitHub Repository](https://github.com/shinlms404/prettier-config)
- [Issues](https://github.com/shinlms404/prettier-config/issues)
- [npm Package](https://www.npmjs.com/package/@shinlms404/prettier-config)
