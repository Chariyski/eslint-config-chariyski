<h1 align="center">eslint-config-defaults</h1>

<p align="center">
  <a href="https://nodei.co/npm/eslint-config-chariyski/">
    <img src="https://nodei.co/npm/eslint-config-chariyski.png?compact=true">
  </a>
</p>

<h4 align="center">
  A composable set of ESLint configurations.
</h4>

***

## Installation

Install this config package and ESLint:

```bash
$ npm install --save-dev eslint eslint-config-chariyski
```

## Usage

### Full Configurations

This package includes the following complete and ready to use configurations:

- `chariyski/configurations/es5` - ES5 config
- `chariyski/configurations/es5-browser` - ES5 + browser
- `chariyski/configurations/es5-node` - ES5 + node
- `chariyski/configurations/es6` - ES6 config
- `chariyski/configurations/es6-browser` - ES6 + browser
- `chariyski/configurations/es6-node` - ES6 + node
- `chariyski/configurations/es6-react` - ES6 + react

###### Extend ESLint

To consume and extend a config in ESLint just add the extends attribute to your `.eslintrc`. For
more details about how shareable configs work, see the
[ESLint documentation](http://eslint.org/docs/developer-guide/shareable-configs).

```js
---
  "extends": "chariyski/configurations/es6-browser"
```

```yaml
---
"extends":
  - "defaults/configurations/es6-browser"
```

**NOTE:** Extending multiple complete configs can cause unexpected results, if you need to do this you should consider a [piecemeal config](http://eslint.org/docs/user-guide/configuring.html#extending-configuration-files).

## License

[MIT License](http://opensource.org/licenses/MIT)
