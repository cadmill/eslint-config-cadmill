# eslint-config-cadmill
Eslint configuration

```bash
yarn add --dev eslint-config-cadmill
```

Create a file in your project `.eslintrc.js`

```javascript
module.exports = {
  extends: 'cadmill',
  env: {
    browser: true,
    node: true
  },
}
```
