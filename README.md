# Eslint convention config

### Installing

1. Use the following command to install all the necessary deps (remove the -Y if you don't use Yarn):

```
npx install-peerdeps --dev @dmcardoso/eslint-config-tech-talks -Y
```

2. Add the following code to your package.json:

```
"eslintConfig": {
  "extends": [
    "@dmcardoso/eslint-config-tech-talks"
  ]
},
```

3. Or create a `.eslintrc` file of your project's directory.

```
{
  "extends": [
    "@dmcardoso/eslint-config-tech-talks"
  ]
}
```
