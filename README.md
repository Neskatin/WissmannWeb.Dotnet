# WissmannWeb .NET Essentials - Extension Pack for VS Code

[![Badge for version for Visual Studio Code extension Wissmann-Web.wissmannweb-dotnet](https://vsmarketplacebadge.apphb.com/version/Wissmann-Web.wissmannweb-dotnet.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-dotnet) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Wissmann-Web.wissmannweb-dotnet.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-dotnet) [![Rating](https://vsmarketplacebadge.apphb.com/rating-star/Wissmann-Web.wissmannweb-dotnet.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-dotnet) [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)

This extension pack for Visual Studio Code adds extensions that are amazingly useful for .NET development.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

> As tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Here are some of my recommended settings. These are optional, but I get asked a lot for them, so here they are.

### Editor settings

For the editor setting see [WissmannWeb.Editor](https://marketplace.visualstudio.com/items?itemName=wissmann-web.wissmannweb-editor).

### CSharp settings

```json
  "files.watcherExclude": {
    "**/bin/**": true,
    "**/obj/**": true
  },
  "search.exclude": {
    "**/bin": true,
    "**/obj": true
  },

  "omnisharp.enableEditorConfigSupport": true,
  "omnisharp.enableRoslynAnalyzers": true,
```

## Included

Here is the list of extensions the pack includes:

- [WissmannWeb.Editor](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-editor) - My prefered VS Code Editor extentions.
- [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) - C# Support
