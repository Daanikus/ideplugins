# CodeLingo Capture extenstion for VSCode

This plugin allows the user to create a new Rule in their [CodeLingo dashboard](https://dash.codelingo.io) by capturing a snippet
of code from within VSCode.

## Installation

You will need `vsce` installed to build the extension: `npm install -g vsce`

1. From `ideplugins/vscode`, run `vsce package`
2. Install the plugin with `code --install-extension codelingo-0.0.1.vsix`

## Usage

1. Select some problematic code
2. Press ctrl + shift + P to bring up the command window
3. Search for CodeLingo Capture plugin
4. Enter a brief Rule description when prompted
5. You will be provided a link to view your new Rule on the dashboard
