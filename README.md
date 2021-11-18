# CBS social app from Kvalifik

An associated project with Kvalifik consultancy

# Expo
```expo``` commands work in native terminal, not in VS Code's terminal
# Prettier

## Edit formats in package.json

```json
"prettier": {
"bracketSpacing": true,
"jsxBracketSameLine": true,
"bracketSameLine": true,
"singleQuote": true,
"tabWidth": 4,
"trailingComma": "all",
"arrowParens": "avoid"
},
```
### Check if there files that not having the latest linting

```zsh
npx prettier --check .
```

### Apply the new style

```zsh
npx prettier --write .
```