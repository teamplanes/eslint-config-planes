# `eslint-config-planes`

### Install

```sh
npx install-peerdeps eslint-config-planes -Y -d

# Optional - install prettier config
yarn add -D prettier-config-planes
```

Then create an `.eslintrc` or update your `package.json` with an
`"eslintConfig"` key, and add the following:

For React:
```json
// package.json
"eslintConfig": {"extends": "eslint-config-planes"}
"prettier": "prettier-config-planes"

// .eslintrc
{"extends": "eslint-config-planes"}
```

For Node:
```json
// package.json
"eslintConfig": {"extends": "eslint-config-planes/node"}
"prettier": "prettier-config-planes"

// .eslintrc
{"extends": "eslint-config-planes/node"}
```
