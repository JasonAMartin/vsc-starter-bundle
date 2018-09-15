# FAST START

#### Setting up a great VSC environment to get coding now.

This extension pack contains a lot of great extensions that I use often and I've also included a handful of themes.

I love **[Visual Studio Code](https://code.visualstudio.com/)** and am always telling people about it.

The pain point for them seemed to be installing extensions (knowing what to install, setting up, etc). I wanted a way to share my own dev enviornment to help them get going instantly to remove the friction.

Languages I generally code with when using VSC:

- JavaScript + framework roulette (and Node/etc)
- PHP
- Python
- Ruby
- LUA
- Elixir
- C# / Unity3D (game development)

### SOME COOL THINGS YOU CAN DO RIGHT AWAY

- Use the project manager to organize your projects (shift+cmd and start typing "project" for more)
- Enjoy knowing when your code is getting out of control thanks to vscode-codemetrics.
- Get quick GIT info on each line thanks to Git Lens.
- Have a fast way to execute NPM scripts via a panel thanks to npm-script.
- Various intellisense and language packs to make working with the languages much better than the default experience.
- Nice highlighting for TODO: and FIXME: notes.
- Get import cost info for your JS files and find heavy imports thanks to import-cost.
- and more!

## RECOMMENDED USER SETTINGS

Here's the user settings I'm currently using. Just open user settings in VSC and paste this JSON into there.

These settings are off a Windows machine, so if you're on Linux or Windows, change the editor.fontFamily to something appropriate and you can remove the git.path setting.

And dont' forget to peek at the overall settings because there's a ton you can tweak.

**These settings will get you running right away.**

```
{
    "editor.fontFamily": "Liberation Mono",
    "editor.fontSize": 14,
    "editor.rulers": [150],
    "editor.tabSize": 2,
    "editor.cursorStyle": "block",
    "editor.formatOnPaste": true,
    "editor.formatOnSave": true,
    "files.trimTrailingWhitespace": true,
    "workbench.iconTheme": "vscode-icons",
    "codemetrics.basics.CodeLensHiddenUnder": 5,
    "csharp.format.enable": false,
    "workbench.colorTheme": "eppz!",
    "codemetrics.basics.ComplexityLevelExtremeDescription": "Most fail, this one has.",
    "codemetrics.basics.ComplexityLevelHighDescription": "This one has failed ...",
    "codemetrics.basics.ComplexityLevelNormalDescription": "Starting to fail.",
    "codemetrics.basics.ComplexityLevelLowDescription": "Readable...",
    "codemetrics.basics.ComplexityLevelNormal": 8,
    "codemetrics.basics.ComplexityLevelHigh": 12,
    "material-icon-theme.showUpdateMessage": false,
    "vsicons.dontShowNewVersionMessage": true,
    "telemetry.enableTelemetry": false,
    "npm.enableScriptExplorer": true,
    "workbench.colorCustomizations": {
        "editorIndentGuide.activeBackground": "#20b0f3"
    },
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "git.path": "C:\\Program Files\\Git\\cmd\\git.exe",
    "gitlens.historyExplorer.enabled": true,
    "auto-close-tag.SublimeText3Mode": true,
    "auto-close-tag.enableAutoCloseSelfClosingTag": true,
    "todohighlight.isCaseSensitive": true,
    "todohighlight.keywords": [
        "REVIEW:",
        {
            "text": "DEPRECATED:",
            "color": "white",
            "backgroundColor": "red",
            "overviewRulerColor": "grey"
        },
        {
            "text": "STUB:",
            "color": "#000",
            "backgroundColor": "#7EC0EE",
        }
    ],
    "materialTheme.fixIconsRunning": false,
}
```

# EXTENSIONS BREAKDOWN

Here's a list of extensions in this pack along with any relevant notes.

### GENERAL IMPROVEMENTS

> [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) :: Colorizes brackets so it's easier to see what section you're in.

> [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) :: Makes it easier to beautify JS/SASS/HTML/CSS/JSON files.

> [Sort Lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines) :: Easy way to sort lines in the editor.

> [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

> [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) :: Easy way to create/manage projects.

> [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) :: Creates a way to bookmark a line of code.

> [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) :: Creates closing tags, which VSC doesn't do out the box.

> [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) :: When you rename a tag, this will rename the closing tag as well.

> [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) :: Adds more code formatting functionality.

> [Code Outline](https://marketplace.visualstudio.com/items?itemName=patrys.vscode-code-outline) :: Provides a code outline in explorer for many languages.

> [TODO Hightlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) :: Adds highlighting when you put a TODO or FIXME in your code. You can add more words and styles too. If you're using the recommended settings, you already have those plus STUB, REVIEW and DEPRECATED.

> [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) :: Shows colors for hex colors it finds in code.

> [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) :: Debugging JS code in Chrome.

> [Codemetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics) :: Computes code complexity in JS / TS / LUA.

> [Formatting Toggle](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) :: Quick way to toggle formatting. It puts a one-click toggle in the bottom bar.

> [VS Code Icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) :: Provides awesome icons for VSC.

> [Copy Relative Path](https://marketplace.visualstudio.com/items?itemName=alexdima.copy-relative-path) :: Drop menu off file will now have 'Copy Path' that copies over the relative path of the file.

> [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) :: Autocompletes filenames.

> [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff) :: Ability to diff text sections in file or in multiple files.

> [DotJoshJohnson.xml](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff) :: XML formatting/tooling.

> [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) :: Gives you a way to do REST calls in VSC.

### VSC THEMES

> [Base 16 Ocean Kit](https://marketplace.visualstudio.com/items?itemName=chipcollier.Theme-OceanKit) :: Light/Dark Base 16 Ocean Theme.

> [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) :: Material-based themes.

> [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) :: One Dark Pro Theme.

> [Eppz](https://marketplace.visualstudio.com/items?itemName=eppz.eppz-code) :: C# Unity Theme.

> [Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code) :: Nord Theme.

> [Palenight Material](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme) :: Palenight Material Theme.

### ANGULARJS / ANGULAR

> [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

> [Angular TS Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

> [Angular Highlighting](https://marketplace.visualstudio.com/items?itemName=nwallace.language-vscode-javascript-angular2)

> [Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) :: Syntax highlighting, code completion, etc.

### C# / UNITY3D

> [ShaderLab](https://marketplace.visualstudio.com/items?itemName=amlovey.shaderlabvscodefree) :: Unity shaderlab.

> [Shader Languages Support](https://marketplace.visualstudio.com/items?itemName=slevesque.shader) :: Shader languages support.

> [C# XML Doc Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment) :: Generates XML doc comments.

> [Unity Tools](https://marketplace.visualstudio.com/items?itemName=Tobiah.unity-tools)

> [C# Fix Format](https://marketplace.visualstudio.com/items?itemName=Leopotam.csharpfixformat)

> [Unity Debug](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) :: Debugger extension for Unity.

> [C# Snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets)

> [C# Support](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

> [Unity Code Snippets](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets)

> [Unity Snippets](https://marketplace.visualstudio.com/items?itemName=YclepticStudios.unity-snippets)

### DOCKER

> [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker) :: Adds syntax highlighting, commands, hover tips, and linting for Dockerfile and docker-compose files.

### ELIXIR

> [Elixir Linting](https://marketplace.visualstudio.com/items?itemName=iampeterbanjo.elixirlinter)

> [Elixir Support](https://marketplace.visualstudio.com/items?itemName=mjmcloug.vscode-elixir)

> [Elixir Support & Debugger](https://marketplace.visualstudio.com/items?itemName=JakeBecker.elixir-ls)

### GIT

> [GIT Project Manager](https://marketplace.visualstudio.com/items?itemName=felipecaputo.git-project-manager)

> [GIT Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) :: Provides a good way to visualize GIT activity, such as providing GIT data at the ends of lines showing when it was last modified, commit message, etc.

> [GIT History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) :: GIT history, search, log and more.

### GO

> [Go](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go) :: Rich Go language support for Visual Studio Code.

### JAVASCRIPT MISC

> [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis) :: Automatically generate JSdoc comments for JS/TS files.

> [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest) :: A way to use Jest in the IDE.

> [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) :: Integrates ESLint into VSC.

> [Exports Autocomplete](https://marketplace.visualstudio.com/items?itemName=capaj.vscode-exports-autocomplete) :: Helps VSC autocomplete JS exports.

> [StandardJS Styled Snippets](https://marketplace.visualstudio.com/items?itemName=capaj.vscode-standardjs-snippets) :: More JS snippets.

> [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) :: Displays the size of the imported package.

> [Javascript ES6 Code Snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) :: Even more JS snippets.

> [Stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint) :: Lints CSS/SCSS/Less with Stylelint.

> [Sass Indented](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented) :: Adds indented syntax ability for Sass.

> [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint) :: Integrates TS linter.

### LUA

> [Lua](https://marketplace.visualstudio.com/items?itemName=keyring.Lua) :: Add Lua language support.

### NODE JS / NPM

> [NPM Scripts](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) :: Adds commands to runs NPM scripts.

> [NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) :: Add autocomplete for imports.

> [Search Node Modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules) :: Easy way to search the node modules folder.

### PHP

> [PHP Intellisense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense) :: Adds more PHP Intellisense.

### PYTHON

> [Python](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense) :: Must-have for Python. Adds a lot of support (Intellisense, linting, debugging, unit tests, formatting, and more).

### REACT

> [React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets) :: React snippets.

### RUBY

> [Ruby Solargraph](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph) :: Provides intellisense and inline doc for Ruby.

> [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby) :: Language support and debugging.

### VUE

> [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets) :: VueJS snippets.

> [Vuetr](https://marketplace.visualstudio.com/items?itemName=octref.vetur) :: VueJS tooling (syntax highlighting, linting, debugging, formatting, etc).

## **Go forth & code...**
