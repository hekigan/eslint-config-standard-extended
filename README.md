# Standard extended - ESLint Shareable Config

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs), based of  [Standard config](https://github.com/feross/eslint-config-standard) from Feross
This module is for advanced users.


## Install

```bash
npm install eslint-config-standard-extended
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Standard Style shareable config, first run this:

```bash
npm install --save-dev eslint-config-standard-extended
```

Then, add this to your .eslintrc file:

```
{
  "extends": "standard-extended"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.
