# Quantum

Take the leap with your editor and start coding in the New Age. This Extension pack includes popular VS Code extensions for Node.js development to be used as an add-on to the Quantum Extension pack or by itself.

## What's in the Box

### Node.js Extension Pack

* [ES Lint](vscode:extension/dbaeumer.vscode-eslint) - Integrates [ESLint](http://eslint.org/) into VS Code.
* [npm](vscode:extension/eg2.vscode-npm-script) - Run npm scripts from the command palatte and validate the installed modules defined in `package.json`.
* [JavaScript (ES6) Snippets](vscode:extension/xabikos.JavaScriptSnippets) - Adds code snippets for JavaScript development in ES6 syntax.
* [Search node_modules](vscode:extension/jasonnutter.search-node-modules) - Quickly search for node modules in your project.
* [NPM IntelliSense](vscode:extension/christian-kohler.npm-intellisense) - Adds IntelliSense for npm modules in your code.
* [Path IntelliSense](vscode:extension/christian-kohler.path-intellisense) - Autocompletes filenames in your code.

## Settings.JSON

Feel free to use these as a base to get started customizing your editor.

```JSON
{
  "editor.autoClosingBrackets": "always",
  "editor.autoClosingQuotes": "always",
  "editor.formatOnSave": false,
  "editor.minimap.enabled": false,
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "files.associations": {
    "*.scpt": "shellscript"
  },
  "git.autoStash": true,
  "git.confirmForcePush": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "terminal.integrated.rendererType": "dom",
  "terminal.integrated.shell.osx": "/bin/zsh",
  "window.zoomLevel": 0,
  "workbench.colorTheme": "Monokai Pro (Filter Spectrum)",
  "workbench.iconTheme": "material-icon-theme",

  "workbench.startupEditor": "readme",
  "[javascript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  }
}
```

**Enjoy!**
