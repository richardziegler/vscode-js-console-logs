## Improved Javascript Console Logs

Easily insert and remove console.log statements, by Richard Ziegler  
Fork of [vscode-js-console-utils](https://github.com/whtouche/vscode-js-console-utils) by [@whtouche](https://twitter.com/whtouche)

## Installing

This extension is not on the marketplace. To install please do the following:

**Install Visual Studio Code Extension package globally via npm**
```
npm install -g vsce
```
**From the root folder of the project, package the extension with this command**

```
vsce package
```
**Install the package with VSCE (Version 1.0.0 used in this example)**
```
vsce --install-extension --vscode-js-console-logs-1.0.0.vsix
```

## Usage

With selection:
* Highlight a variable (or really any text)
* Press Cmd+Shift+L
* The output (on a new line) will be: console.log('variable: ', variable)

With selection and wanting JSON.stringify():
* Highlight a variable (or really any text)
* Press Cmd+Shift+J
* The output (on a new line) will be: console.log('variable: ', JSON.stringify(variable))

Without selection:
* Press Cmd+Shift+L
* The output (on the same line) will be: console.log()

To remove console.logs:
* Press Cmd+Shift+D
* This will delete all console.log statements in the current document

## License
[MIT License](LICENSE)
