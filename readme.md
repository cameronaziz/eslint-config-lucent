ESLint Config for ReactJS
=========================

## About ##
ESLint configuration based off of [Airbnb's ESLint][airbnbNpm] configuration. Many of the errors will not crash application so they have been reduced to warnings.

## Configuration ##
1. `npm i -D eslint-config-lucent`
1. Create a `.eslintrc` file in the root directory
2. Add the following:

    `{`
      `"extends": "eslint-config-lucent"`
    `}`
3. We suggest to use `babel-eslint` to transpile code.

    a. `npm i -D eslint babel-eslint`

    b. Use the following for `.eslintrc`

    `{`
      `"extends": "eslint-config-lucent",`
      `"parser": "babel-eslint"`
    `}`

[airbnbNpm]: https://www.npmjs.com/package/eslint-config-airbnb
