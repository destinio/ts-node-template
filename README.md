## Node Template

## Usage/Install

`gh repo create <NEW_REPO_NAME> --template destinio/ts-node-template`

## Configs

> TODO: Add Gist with the following

### .editorconfig

```js
root = true

[*]
charset = utf-8
indent_style = space
indent_size = 2
end_of_line = lf
insert_final_newline = false
trim_trailing_whitespace = true
```

### .prettierrc

```json
{
  "arrowParens": "avoid",
  "bracketSpacing": true,
  "printWidth": 100,
  "semi": false,
  "singleQuote": true,
  "tabWidth": 2,
  "trailingComma": "es5"
}
```

### tsconfig.json

```json
{
  "compilerOptions": {
    "target": "ES5",
    "module": "es2020",
    "moduleResolution": "node",

    "rootDir": "./src",
    "outDir": "./dist",

    "strict": true,
    "noImplicitAny": true,
    "noUnusedParameters": true,

    "esModuleInterop": true
  }
}
```

### .npmrc

```
package-lock=false
registry=https://registry.npmjs.org/
```
