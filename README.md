![wafa prettier conifg](images/logo.png)
# Prettier-config 

A shared prettier configuration to use in digital wafa projects

***

## Installation

```
npm install --save-dev prettier @digital-wafa/prettier-config
```

## Usage
Add a `prettier` property in your `package.json`. See the [Configuration docs](https://prettier.io/docs/en/configuration.html).

```json
"prettier": "@digital-wafa/prettier-config"
```

## Extending

If you find yourself in the situation where you have to change This configuration, here is how to do it.

To extend a configuration you hava to create a `prettier.config.js` or `.prettierrc.js` file like the example below:

```javascript
module.exports = {
    ...require('@digital-wafa/prettier-config'),
    "useTabs": false,
    "semi": true
};
```

