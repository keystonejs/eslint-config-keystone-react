# eslint-config-keystone-react

Shareable ESLint Config for Coding Standards used in [KeystoneJS](http://keystonejs.com) with React Extensions

Extends [eslint-config-keystone](https://github.com/keystonejs/eslint-config-keystone)

## Installation

Install the following dependencies in your project:

```
npm install --save-dev eslint eslint-plugin-react eslint-config-keystone eslint-config-keystone-react
```

Then add an `.eslintrc` file to your project that extends the `keystone` config:

```
{
  "extends": [
     "keystone-react"
  ]
}
```

You can do this from the OS X terminal by running this line in your project folder:

```
echo -e '{\n  "extends": [\n    "keystone-react"\n  ]\n}' >> .eslintrc
```

Additional configuration can be added to `.eslintrc` that extends or overrides the keystone defaults.

## License

MIT. Copyright (c) 2016 Jed Watson.
