# tictactoe-t1

FE스터디 2주차

* <https://nkcroft.github.io/tictactoe-t1/>
* <https://react.dev/learn/tutorial-tic-tac-toe>

## Setup

### .editrconfig

```conf
[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[*.{md}]
indent_size = 4
```

### vite --template react

* <https://vitejs.dev/guide/>

```sh
yarn create vite . --template react
```

### eslint - migrating to standard rules

* <https://standardjs.com/readme-kokr.html>
* <https://github.com/standard/eslint-config-standard>

```sh
yarn add -D eslint-config-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-n
```

#### .eslintrc.cjs

```js
extends: [
  // 'eslint:recommended',
  'standard',
  'plugin:react/recommended',
  'plugin:react/jsx-runtime',
  'plugin:react-hooks/recommended'
],
```

#### Rules

* `'import/no-absolute-path': 'off'`

## Deployment

* <https://pages.github.com/>

### GitHub Actions

* <https://github.com/JamesIves/github-pages-deploy-action>
* <https://github.com/marketplace/actions/deploy-to-github-pages>

