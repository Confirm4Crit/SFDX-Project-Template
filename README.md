# Instructions

1. Get set up here https://forcedotcom.github.io/salesforcedx-vscode/
2. Pull the project and open it
3. Set a default org to your target box.
4. Download the ESLint and Prettier Extensions on VS Code Marketplace.
5. NPM Install the package.json.
6. Adjust the following settings to properly hook up prettier/lint formatting to VSCode

```
"prettier.eslintIntegration": true,
"eslint.nodePath": "./node_modules", //Or a global nodePath if you want.
"[javascript]": {
"editor.defaultFormatter": "esbenp.prettier-vscode" // This'll make format command in vscode follow prettier, which will follow ESLint
},
"[apex]":{
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
```
