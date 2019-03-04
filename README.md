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
    "editor.minimap.enabled": false
}

"[html]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": false,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false
}

"[yaml]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false
}

"[javascript]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false
}

"[typescript]": {
    "editor.autoIndent": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false
}

"[json]": {
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.renderWhitespace": "boundary",
    "editor.minimap.enabled": false
}
```

## Other Recommended settings

Add following in `User` or `Workspace` settings to improve your development experience in `Angular`.

```
"workbench.iconTheme": "material-icon-theme",
"breadcrumbs.enabled": true,

"files.associations": {
    ".huskyrc": "json",
},
"files.exclude": {
    "**/.git": true
},

"gitlens.views.repositories.files.layout": "tree",

"prettier.singleQuote": true,
"prettier.printWidth": 140
```


## Extensions
* [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin) - Enables TSLint support
* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - Improves editing experience of external templates
* [Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) - Improves editing experience of inline templates.
* [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) - AI assisted developer productivity
* [Angular Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)- Angular snippets by John Papa
* [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Improves Git capabilities
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Enables Prettier support
* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) -  Enables EditorConfig support
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) -  Use material design icons in explorer
* [Chrome Debugger](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) - Enables Chrome debugging
* [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker) -  Enables docker support
* [Browser Preview](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview) - Enables browser preview