# eslint-plugin-jest-dom

[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors)

lint rules for use with [jest-dom](https://github.com/testing-library/jest-dom).

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-jest-dom`:

```
$ npm install eslint-plugin-jest-dom --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-jest-dom` globally.

## Usage

Add `jest-dom` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["jest-dom"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "jest-dom/prefer-checked": "error",
    "jest-dom/prefer-enabled-disabled": "error",
    "jest-dom/prefer-required": "error"
  }
}
```

## Recommended Configuration

This plugin exports a recommended configuration that enforces good
`jest-dom` practices _(you can find more info about enabled rules
in [Supported Rules section](#supported-rules))_.

To enable this configuration use the `extends` property in your
`.eslintrc` config file:

```json
{
  "extends": ["plugin:jest-dom/recommended"]
}
```

## Supported Rules

✔️ indicates that a rule is recommended for all users.

🛠 indicates that a rule is fixable.

<!-- __BEGIN AUTOGENERATED TABLE__ -->

| Name                                                                                                                                   | ✔️  | 🛠   | Description                                                 |
| -------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | ----------------------------------------------------------- |
| [prefer-checked](https://github.com/testing-library/eslint-plugin-jest-dom/blob/master/docs/rules/prefer-checked.md)                   | ✔️  | 🛠   | prefer toBeChecked over checking attributes                 |
| [prefer-enabled-disabled](https://github.com/testing-library/eslint-plugin-jest-dom/blob/master/docs/rules/prefer-enabled-disabled.md) | ✔️  | 🛠   | prefer toBeDisabled or toBeEnabled over checking attributes |
| [prefer-required](https://github.com/testing-library/eslint-plugin-jest-dom/blob/master/docs/rules/prefer-required.md)                 | ✔️  | 🛠   | prefer toBeRequired over checking properties                |

<!-- __END AUTOGENERATED TABLE__ -->

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/benmonro"><img src="https://avatars3.githubusercontent.com/u/399236?v=4" width="100px;" alt="Ben Monro"/><br /><sub><b>Ben Monro</b></sub></a><br /><a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=benmonro" title="Documentation">📖</a> <a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=benmonro" title="Code">💻</a> <a href="#example-benmonro" title="Examples">💡</a> <a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=benmonro" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://nickmccurdy.com/"><img src="https://avatars0.githubusercontent.com/u/927220?v=4" width="100px;" alt="Nick McCurdy"/><br /><sub><b>Nick McCurdy</b></sub></a><br /><a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=nickmccurdy" title="Code">💻</a> <a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=nickmccurdy" title="Documentation">📖</a> <a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=nickmccurdy" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://twitter.com/gnapse"><img src="https://avatars0.githubusercontent.com/u/15199?v=4" width="100px;" alt="Ernesto García"/><br /><sub><b>Ernesto García</b></sub></a><br /><a href="https://github.com/testing-library/eslint-plugin-jest-dom/commits?author=gnapse" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
