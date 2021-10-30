<div align="center">
<h1>@pokayoke/prettier-config 🎨</h1>
</div>

---

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
"@matthamil/prettier-config"
```

## Overriding or Extending Config

Import this package in a `.prettierrc.js` file and add your own config options:

```js
module.exports = {
  ...require("@pokayoke/prettier-config"),
  semi: false,
};
```





