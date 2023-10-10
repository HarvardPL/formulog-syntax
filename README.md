# Formulog Syntax

Language support for [Formulog](https://github.com/HarvardPL/formulog) in Visual Studio Code.

## Features

Syntax highlighting for `.flg` files.
To install, clone this repository to somewhere that is NOT the `$HOME/.vscode/extensions` folder.
Then run `code --install-extension path/to/formulog-syntax-0.1.0.vsix` and restart Code.

To uninstall, run `code --uninstall-extension undefined_publisher.formulog-syntax`.

## Building

(You shouldn't need to do this unless you are making changes.)
Run `make`.

Dependencies:

- npm
- js-yaml
- vsce

## TODO

- Publish to VS Code Extension Marketplace