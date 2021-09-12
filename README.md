# vscode-settings

```js
{
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontFamily": "JetBrains Mono, Consolas, Monaco",
    "editor.fontLigatures": true,
    "editor.fontWeight": "600",
    "editor.lineHeight": 24,
    "editor.rulers": [80, 120],
    //liberar emmet no js
    "emmet.syntaxProfiles": {
        "javascript": "jsx",
    },
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
    },
    "[sass]": {
        "editor.tabSize": 2
    },
    "[scss]": {
        "editor.tabSize": 2
    },
    "[css]": {
        "editor.tabSize": 2
    },
    "[html]": {
        "editor.tabSize": 2
    },
    "[javascript]": {
        "editor.tabSize": 2
    },
    "window.zoomLevel": -1,
    "workbench.startupEditor": "newUntitledFile",
    "explorer.compactFolders": false,
    "workbench.colorTheme": "Omni",
    /*"editor.wordWrap": "on",*/


    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations": true,

    "javascript.updateImportsOnFileMove.enabled": "always",
    "typescript.updateImportsOnFileMove.enabled": "never",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
      },
    
    "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json"
    },
    "javascript.suggest.autoImports": true,
    "typescript.suggest.autoImports": true,
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.rulers": [
            80
        ],
        "editor.selectionHighlight": false,
        "editor.suggest.snippetsPreventQuickSuggestions": false,
        "editor.suggestSelection": "first",
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": false
    },
}

```
