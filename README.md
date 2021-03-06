# Azure CLI Tools

Scrapbooks for developing and running commands with the [Azure CLI](https://aka.ms/AzureCLI2).

Create `.azcli` files and use these features:
- IntelliSense for commands and their arguments.
- Snippets for commands, inserting required arguments automatically.
- Run the current command in the integrated terminal.
- Run the current command and show its output in a side-by-side editor.
- Show documentation on mouse hover.
- Display current subscription and defaults in status bar.

![Azure CLI Tools in Action](images/in_action.gif)

## Known Issues

On OSX the extension currently does not work with the Homebrew install of the Azure CLI. This can be worked around by installing the Azure CLI through the install script (see https://aka.ms/GetTheAzureCLI).

## Release Notes

### 0.3.0

- Fix [delayed completion proposals on Windows](https://github.com/Microsoft/vscode-azurecli/issues/19).
- Fix [completion proposals hang when az crashes](https://github.com/Microsoft/vscode-azurecli/issues/20).

### 0.2.0

- Add 'Azure' marketplace category.
- Fix [failure when running commands in the Terminal](https://github.com/Microsoft/vscode-azurecli/issues/16).

### 0.1.0

- Improve argument sort order in IntelliSense.
- Fix handling of spaces in az's path on Windows. Did not work with MSI install.
- Fix version check for older versions. Should show a message asking to update az.
- Smaller bugfixes.

### 0.0.1

Initial release.

## Contributing

File bugs and feature requests in [GitHub Issues](https://github.com/Microsoft/vscode-azurecli/issues).

Checkout the source code in the [GitHub Repository](https://github.com/Microsoft/vscode-azurecli).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License
[MIT](LICENSE)