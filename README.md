# Parinfer for Visual Studio Code [![Build Status](https://travis-ci.org/shaunlebron/vscode-parinfer.svg?branch=master)](https://travis-ci.org/shaunlebron/vscode-parinfer) <a href="https://standardjs.com"><img src="https://img.shields.io/badge/code_style-standard-brightgreen.svg" alt="Standard - JavaScript Style Guide"></a>

Modified toggleMode function so it toggles between "SMART_MODE" and "DISABLED"

Installing steps:

1. Download repo
2. Install vsce
3. `vsce package --no-yarn`
4. In Visual Code press `CTRL/CMD + SHIFT + P` > then type `Shell Command: Install 'code' command in PATH` then press `enter`
5. `npm install parinfer@3.12.0`
6. `code --install-extension vscode-parinfer-0.6.3.vsix --force`



A [Parinfer] package for [Visual Studio Code].

## Demo

![demo](parinfer.gif)

### ChangeLog

[ChangeLog](https://github.com/shaunlebron/vscode-parinfer/releases)

## License

[MIT License](LICENSE.md)

[Parinfer]:http://shaunlebron.github.io/parinfer/
[Visual Studio Code]:https://code.visualstudio.com
