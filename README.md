# Louffee StyleLint Configuration

*A great way to style styles.*

> **Note**: The configuration is based on the [StyleLint](https://stylelint.io/) plugin for the IDE or code editor of your choice, and is compatible with the ESLint ecosystem present in the [NPM Package of same name](https://npmjs.com/package/stylelint).

[![Downloads](https://img.shields.io/npm/dm/stylelint-config-louffee.svg)](https://www.npmjs.com/package/stylelint-config-louffee)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/louffee/stylelint-config-louffee?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

## Installation

Install the package, follow the instructions according to the package manager of your choice, we ranked the top three most popular ones:

With **NPM**

```bash
npm install --dev stylelint-config-louffee
```

With **Yarn**

```bash
yarn add -D stylelint-config-louffee
```

With **PNPM**

```bash
pnpm install --dev stylelint-config-louffee
```

## Usage 📖

To use the Louffee’s configuration, create a new file named `.stylelintrc.js` in the root of your project, and add the following content:

```js
module.exports = require('stylelint-config-louffee');
```

(Optional) Also create a `.stylelintignore` file in the root of your project, then add the following line:

```plain
node_modules
```
