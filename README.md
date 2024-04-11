## Minhas configuracões do VSCode.

```
{
    // -- workbench config
    "workbench.colorTheme": "Vesper ++",
    "workbench.productIconTheme": "fluent-icons",
    "workbench.startupEditor": "none",
    "workbench.tree.indent": 15,
    "workbench.activityBar.location": "hidden", // => sidebar
    "workbench.editor.labelFormat": "short", // => formato nome do arquivo
    "workbench.statusBar.visible": false, // => barra inferior
    "workbench.editor.showTabs": "multiple", // => exibir tabs/abas
    "workbench.iconTheme": "symbols",
    "editor.fontFamily": "Jetbrains Mono",
    "workbench.layoutControl.enabled": false,
    "workbench.sideBar.location": "right",
  
    // -- editor config
    "editor.formatOnPaste": true,
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "editor.lineHeight": 24,
    "editor.rulers": [80, 120], // => linhas verticais como limite
    "editor.renderLineHighlight": "gutter",
    "editor.codeActionsOnSave": {
      "source.addMissingImports": "explicit",
      "source.fixAll.eslint": "always",
      "source.fixAll": "always",
      // "source.organizeImports": "explicit" //conflito com o eslint-prettier
    },
    // "window.zoomLevel": 1, // aumenta o zoom
    "editor.scrollbar.vertical": "hidden",
    "editor.cursorBlinking": "expand",
    "editor.overviewRulerBorder": false,
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.hideCursorInOverviewRuler": true,
    "editor.guides.indentation": false,
    "editor.matchBrackets": false,
    "editor.glyphMargin": false,
    "editor.wordWrap": "bounded",
    "editor.wordWrapColumn": 80,
    "editor.formatOnSave": false,
    "editor.semanticHighlighting.enabled": false,
    "window.commandCenter": false,
  
    // -- terminal config
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "terminal.integrated.env.windows": {},
  
    // -- emmet config
    "emmet.syntaxProfiles": {
      "javascript": "jsx"
    },
    "emmet.includeLanguages": {
      "javascript": "javascriptreact",
      "typescript": "typescriptreact"
    },
  
    // -- javascript config
    "[javascript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "javascript.suggest.autoImports": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "javascript.suggest.paths": false,
  
    // -- typescript config
    "[typescript]": {
      // "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescriptreact]": {
      // "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "typescript.suggest.paths": false,
    "typescript.suggest.autoImports": true,
  
    // -- dart config
    "dart.hotReloadOnSave": "all",
    "dart.hotReloadProgress": "statusBar",
  
    // -- others config
    "[jsonc]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[css]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "explorer.compactFolders": false,
    "breadcrumbs.enabled": false,
  
    // -- extensions config
    "tabnine.experimentalAutoImports": true,
    "cSpell.diagnosticLevel": "Hint", // => marcador spell checker.
    "cSpell.language": "en,pt,pt_BR",
    // "prettier.singleQuote": true,
    // "prettier.semi": false,
    // "prettier.jsxSingleQuote": true,
    "indenticator.width": 0.1,
    "indenticator.color.dark": "rgba(255, 255, 255, 0.05)",
    // "symbols.hidesExplorerArrows": true, // => esconder setinhas das pastas.
    "console-ninja.featureSet": "Community",
    "symbols.hidesExplorerArrows": false,
    "[json]": {
      "editor.defaultFormatter": "vscode.json-language-features"
    },
    "window.menuBarVisibility": "compact",
    "[html]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
  }
```
