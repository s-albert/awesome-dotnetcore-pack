# Awesome DotNetCore Pack

A collection of useful, stable and best rated dotnetcore/C# extensions, which build a productive IDE. If you are also an angular/typescript developer check out the [Awesome Angular Pack](https://marketplace.visualstudio.com/items?itemName=salbert.awesome-angular-pack), which reuses extensions that offer support for both environments.

## C# and DotNetCore

* [C# for Visual Studio Code (powered by OmniSharp)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

* [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)
  This VSCode extension provides extensions to the IDE that will hopefully speed up your development workflow.

* [C# Snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets)

* [Super Sharp (C# extensions)](https://marketplace.visualstudio.com/items?itemName=craigthomas.supersharp)
  Provides some missing refactoring features for C#

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [Dotnet Core Essentials](https://marketplace.visualstudio.com/items?itemName=kishoreithadi.dotnet-core-essentials)
  Create, debug, run and publish .Net core/standard applications

* [Essential ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-snippets)
  High quality Code Snippets that boost your ASP.NET Core development productivity

## Code formatting and comments

* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  This plugin attempts to override user/workspace settings with settings found in .editorconfig files. No additional or vscode-specific files are required. As with any EditorConfig plugin, if root=true is not specified, EditorConfig will continue to look for an .editorconfig file outside of the project.

* [XML Documentation Comments Support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
  Generate XML documentation comments for Visual Studio Code.

## Dev Tools

* [IL Viewer for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=josephwoodward.vscodeilviewer)
  IL (Intermediate Language) Viewer for Visual Studio Code allows you to rapidly inspect the IL output of any given C# file.

* [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
  Test Explorer for .NET Core

* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  GitLens supercharges the Git capabilities built into Visual Studio Code. It helps you to visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  Visual Studio Code plugin that autocompletes filenames.

* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  Show TODO, FIXME, etc. comment tags in a tree view

* [Copy text](https://marketplace.visualstudio.com/items?itemName=salbert.copy-text)
  Offers more copy options: Copies text without syntax highlighting, optionally adds metainfo like document name and date.

## Recommended extensions (not included)

* [MSSQL](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
  If you are using the ms sql server.

* If you come from VS development, the [Visual Studio Keymap for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vs-keybindings) might be interesting.

* [Studio Icons](https://marketplace.visualstudio.com/items?itemName=jtlowe.vscode-icon-theme)
  Featuring official icons from the Visual Studio Image Library. These icons have been color optimized to work well for dark, light, and high contrast themes.

## Settings Tipps

* If you do not like vs code telemetry set:

```
"telemetry.enableTelemetry": false
```

* If you do not need 'open editors' and like to use the space for your project files:

```
"explorer.openEditors.visible": 0
```

* Auto save on leaving the editor:

```
"files.autoSave": "onFocusChange"
```

* Enhanced minimap performance by disabling render characters in minimap:

```
"editor.minimap.renderCharacters": false
```
