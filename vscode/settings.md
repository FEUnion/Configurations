### windows版本

```json
{
  "editor.tabSize": 2,
  "vetur.validation.template": false,
  "gitlens.advanced.messages": {
    "suppressGitVersionWarning": true,
    "suppressShowKeyBindingsNotice": true
  },
  "files.associations": {
    "*.vue": "vue"
  },
  //eslint
  "eslint.options": {
    "configFile": "./.eslintrc.js"
  },
  "path-intellisense.mappings": {
    "@": "${workspaceRoot}/src"
},
  
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "html",
    "vue"
  ],
  // Turns auto fix on save on or off.
  "editor.formatOnSave": false,
  "javascript.implicitProjectConfig.experimentalDecorators": true,
  //end
  "window.zoomLevel": 0,
  "editor.wordWrap": "on",
  "gitlens.views.repositories.files.layout": "tree",
  "gitlens.views.fileHistory.enabled": true,
  "gitlens.views.lineHistory.enabled": true,
  "vetur.format.defaultFormatter.html": "js-beautify-html",
  "vetur.format.defaultFormatter.js": "prettier-eslint",
  "vetur.format.defaultFormatterOptions": {
    "js-beautify-html": {
      "wrap_attributes": "force-expand-multiline"
    },
    "prettyhtml": {
      "printWidth": 100,
      "singleQuote": false,
      "wrapAttributes": false,
      "sortAttributes": false,
    },
    "prettier-eslint": {
      "singleQuote": true,
      "semi": false,
      "onePxTransform": true
    }
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "sync.gist": "729dab32b68a58796210ccd0df6e2d5a",
  "sync.forceDownload": false,
  "sync.autoUpload": false,
  "editor.fontSize": 18,
  
  "editor.minimap.enabled": true,
  "breadcrumbs.enabled": true,
  
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorCustomizations": {
    "activityBarBadge.background": "#7CB342",
    "list.activeSelectionForeground": "#7CB342",
    "list.inactiveSelectionForeground": "#7CB342",
    "list.highlightForeground": "#7CB342",
    "scrollbarSlider.activeBackground": "#7CB34250",
    "editorSuggestWidget.highlightForeground": "#7CB342",
    "textLink.foreground": "#7CB342",
    "progressBar.background": "#7CB342",
    "pickerGroup.foreground": "#7CB342",
    "tab.activeBorder": "#7CB342",
    "notificationLink.foreground": "#7CB342",
    "editorWidget.resizeBorder": "#7CB342",
    "editorWidget.border": "#7CB342",
    "settings.modifiedItemIndicator": "#7CB342",
    "settings.headerForeground": "#7CB342",
    "panelTitle.activeBorder": "#7CB342",
    "breadcrumb.activeSelectionForeground": "#7CB342",
    "menu.selectionForeground": "#7CB342",
    "menubar.selectionForeground": "#7CB342",
    "editor.findMatchBorder": "#7CB342",
    "selection.background": "#ff000040"
  },
  "editor.tokenColorCustomizations": {
    "comments": "#7CB342", // 注释
  },
  "sync.forceUpload": true,
  "git.autofetch": true,
  "editor.showFoldingControls": "always",
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "material-icon-theme.activeIconPack": "react_redux",
  "workbench.colorTheme": "One Monokai",
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "typescript.format.semicolons": "remove",
  "prettier.semi": false,
  "autoimport.semicolon": false,
  "autoimport.useSemiColon": false,
  "javascript.format.semicolons": "remove",
  "search.followSymlinks": false,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.autoSaveDelay": 60000,
  "editor.fontFamily": "Inziu IosevkaCC SC,Consolas, 'Courier New', monospace",
  "cSpell.userWords": [
    "contenteditable",
    "defaultdata",
    "getinfosuccess"
  ],
  "editor.renderControlCharacters": true,
  "files.trimTrailingWhitespace": true,
    // 指定每行代码的最佳长度， 如果超出长度则换行。
   "prettier.printWidth": 188,  
}

```
