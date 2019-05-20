# Chance Digital Browserslist Config

Shareable configuration for [Browserslist](https://www.npmjs.com/package/browserslist) following Chance Digital Coding Standards.

## Installation

Install this configuration as a `devDependency` in your project:

```shell
yarn add -D @chancedigital/browserslist-config
```

## Usage

Add this to your `package.json` file:

```json
"browserslist": [
	"extends @chancedigital/browserslist-config"
]
```

Alternatively, add this to `.browserslistrc` file:

```
extends @chancedigital/browserslist-config
```

This package, when imported, returns an array of supported browsers, for more configuration examples including Autoprefixer, Babel, ESLint, PostCSS, and stylelint see the [Browserslist examples](https://github.com/ai/browserslist-example#browserslist-example) repo.
