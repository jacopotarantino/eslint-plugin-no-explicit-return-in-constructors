# eslint-plugin-no-explicit-return-in-constructors

Identifies and flags usage of explicit return statements in JavaScript Classes

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-no-explicit-return-in-constructors`:

```
$ npm install eslint-plugin-no-explicit-return-in-constructors --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-no-explicit-return-in-constructors` globally.

## Usage

Add `no-explicit-return-in-constructors` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "no-explicit-return-in-constructors"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "no-explicit-return-in-constructors/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





