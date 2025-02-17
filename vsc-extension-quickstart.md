# Extension maintainer readme

## Useful links

* [fmn node env in vscode](https://github.com/Schniz/fnm/issues/1317)
* [Publishing](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

## Welcome to your VS Code Extension Pack

[Development quick start guide](https://code.visualstudio.com/api/get-started/your-first-extension)

## What's in the folder

* This folder contains all of the files necessary for your extension pack.
* `package.json` - this is the manifest file that defines the list of extensions of the extension pack.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `Extensions Viewlet` and check your extensions are installed.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

### List current installed extensions

´´´ pwsh
code --list-extensions > installed.lst
´´´

## Build

´´´ pwsh
vsce package
´´´

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on <https://code.visualstudio.com/docs> about publishing an extension.

## Publish

´´´ pwsh
vsce package
´´´

## Docs

* <https://mister-gold.pro/posts/create-vscode-extension-pack/>
