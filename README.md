# mostjs ESLint config

## Usage

### Via package-starter

Use the [package-starter](https://github.com/mostjs/package-starter).

### Via eslintrc

If you don't use the package starter, you can extend `eslint-config-most` in your .eslintrc:

```
npm install --save-dev @most/eslint-config-most
```

```js
{
  'extends': 'most'
}
```

(Note: You can omit the `eslint-config-` prefix since it is automatically assumed by ESLint)

You can override settings by adding them directly into your .eslintrc file.
