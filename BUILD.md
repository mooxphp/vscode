<br>
<p align="center">
    <img src="https://raw.githubusercontent.com/mooxphp/moox/main/art/moox-logo.png" width="200" alt="Moox Logo">
</p>

# Build

This is only an extension package. Use it with VS Code. There is no need to build anything else ;-)

## Prepare

- Edit CHANGELOG.md
- Edit package.json, don't forget the version

## Update package on VSC Marketplace (yep, that's more an internal note)

```bash
npm i -g @vscode/vsce
# See https://www.npmjs.com/package/@vscode/vsce

# Check if it is installed, if necessary
npm list -g

cd vscode
vsce package
# myExtension.vsix generated
vsce publish
# <publisherID>.myExtension published to VS Code Marketplace
```

See https://code.visualstudio.com/api/working-with-extensions/publishing-extension for more information.

Instead of vsce publish, where most of the time the pat expired, you can use the upload on https://marketplace.visualstudio.com/manage/publishers/adrolli
