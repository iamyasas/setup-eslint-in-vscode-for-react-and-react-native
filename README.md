# setup-eslint-in-vscode-for-react-and-react-native
Setup of eslint in VSCode for React &amp; React-Native

1) npm install -g eslint //install eslint globally.
2) install eslint extention in VSCode.
3) npm install --save-dev eslint-config-rallycoding //install default ruleset for the eslint.
4) create .eslintrc file in the root directory.
5) put below content and save

{
  "extends": "rallycoding",
  "globals": {
    "fetch": true
  },
  "rules": {
    "arrow-body-style": 0
  }
}

6) Restart VSCode.

