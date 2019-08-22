# Angular Development Essentials

Curated set of Visual Studio Code extensions to improve your development experience in `Angular`.

## Editor Settings

This pack contributes following language specific editor settings as default. You can override these in `User` or `Workspace` Settings.
```
"[scss]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
}

"[html]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": false,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
}

"[yaml]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
}

"[javascript]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
}

"[typescript]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
}

"[json]": {
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

## Other Recommended settings

Add following in `User` or `Workspace` settings to improve your development experience in `Angular`.

```
"workbench.iconTheme": "material-icon-theme",
"workbench.colorTheme": "Night Owl",
"breadcrumbs.enabled": true,

"files.associations": {
    ".huskyrc": "json",
},
"files.exclude": {
    "**/.git": true
},

"gitlens.views.repositories.files.layout": "tree",

"prettier.singleQuote": true,
"prettier.printWidth": 120

"eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
```


## Extensions
* [Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) - Improves editing experience of inline templates.
* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - Improves editing experience of external templates
* [Angular Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)- Angular snippets by John Papa
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) - Colorizing matching brackets
* [Browser Preview](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview) - Enables browser preview
* [Chrome Debugger](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) - Enables Chrome debugging
* [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker) -  Enables docker support
* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) -  Enables EditorConfig support
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint
* [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Improves Git capabilities
* [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) - AI assisted developer productivity
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) -  Use material design icons in explorer
* [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl) - Theme for the night owls out there
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Enables Prettier support
