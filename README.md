# qmakepro README

Visual Studio Code extension "qmakepro".

## Features

Syntax highlight for QMake project (.pro) files

## Install

1. Make sure you have [Node.js](https://nodejs.org/) installed. Then run:
```bash
    npm install -g @vscode/vsce
```

2. Generate `qmakepro.vsix`:
```bash
    vsce package
```

3. Install `qmakepro.vsix` in VSCode from **Extensions** -> **Views and More Actions...** -> **Install from VSIX...**


## History

### 0.0.1

Initial release of QMake project syntax highlight

### 0.0.2

Fixed line comment style
