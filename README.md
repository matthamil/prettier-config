<div align="center">
<h1>@pokayoke/prettier-config 🎨</h1>
</div>

---

<!-- prettier-ignore-start -->
[![version][version-badge]][package]
[![MIT License][license-badge]][license]
<!-- prettier-ignore-end -->

## Installation

Add this package to your project's `devDependencies`:

```
yarn add -D @pokayoke/prettier-config
```

## Usage

Use this config in one of the following ways:

Reference this package in your `package.json`:

```json
{
  "prettier": "@pokayoke/prettier-config"
}
```

Or, use any of the [supported extensions](https://prettier.io/docs/en/configuration.html) (e.g. `.prettierrc.json`) to export a string:

```
"@pokayoke/prettier-config"
```

## Overriding or Extending Config

Import this package in a `.prettierrc.js` file and add your own config options:

```js
module.exports = {
  ...require("@pokayoke/prettier-config"),
  semi: false,
};
```

<!-- variables -->
[version-badge]: https://img.shields.io/npm/v/@pokayoke/prettier-config?style=flat-square
[package]: https://www.npmjs.com/package/@pokayoke/prettier-config
[license-badge]: https://img.shields.io/github/license/matthamil/prettier-config?style=flat-square
[license]: https://github.com/matthamil/prettier-config/LICENSE



