# VSCode-BananiumPluginPack
Our favorite plugins for our favorite editor :D

Created especially for our team, but you're welcome to use it if it fits your use case as well!

## Committing
If you would like to add a plugin to the pack, commit using the format:

`Add <Plugin Name>`

and insert a description of the plugin and a link to the marketplace page in the extended description. Don't forget to update the Readme as well!

## Building
In order to build a release of the plugin pack, you must install the Yeoman VSCode extension generator: `sudo npm install -g yo generator-code vsce`

Steps to update:
1. `yo code`
2. Input the information found in `package.json` into the prompt for creating a new extension pack.
3. Copy the new content of the generated `package.json` (only the "extensionPack" area).
4. Update the README and CHANGELOG with all relevant change information.
5. Run `vsce package` to create a .vsix file. Don't commit this file.
6. Publish a new release!

For more information, [click here.](https://code.visualstudio.com/docs/extensions/yocode).

## List of Extensions

### General
 - [Atom Keybinds](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings)
 - [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
 - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
 - [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
 - [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

### C#
 - [C# Language Support](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
 - [C# FixFormat](https://marketplace.visualstudio.com/items?itemName=Leopotam.csharpfixformat)

### Java
 - [RedHat Java Language Support](https://marketplace.visualstudio.com/items?itemName=redhat.java)
 - [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)

### Angular
 - [Angular Support](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
 - [Angular2 Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) 
 - [Angular Files](https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files)

### Web (HTML/CSS/JS/TS)
 - [FontAwesome Codes](https://marketplace.visualstudio.com/items?itemName=medzhidov.font-awesome-codes-html)
 - [HTML/CSS Language Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) 
 - [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
 - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
 - [JS Code Snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
 - [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
 - [Beautify css/sass/scss/less](https://marketplace.visualstudio.com/items?itemName=michelemelluso.code-beautifier)

 #### Node.js and NPM
 - [Search node_modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules)
 - [NPM Support for VSCode](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
 - [NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)