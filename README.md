# FiraCode
> [Download](https://github.com/tonsky/FiraCode)

# VS Code Extensions
- Dracula Official: Dracula Theme
- Color Highlight: Sergii Naumov
- EditorConfig for VS Code: EditorConfig
- ESLint: Dirk Baeumer
- Prettier Code Formatter: Esben Petersen
- Rocketseat React Native: Rocketseat
- Rocketseat ReactJS: Rocketseat
- vscode-icons: VSCode Icons Team
- vscode-styled-components: Julien Poissonnier

# VS Code Settings
```
{
    "workbench.colorTheme": "Dracula",
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "editor.fontSize": 14,
    "editor.lineHeight": 24,
    "workbench.iconTheme": "vscode-icons",
    "editor.formatOnSave": false,
    "[typescript]": {
      "editor.formatOnSave": false
    },
    "[typescriptreact]": {
      "editor.formatOnSave": false
    },
    "editor.rulers": [
      80,
      120
    ],
    "editor.tabSize": 2,
    "editor.renderLineHighlight": "gutter",
    "terminal.integrated.fontSize": 14,
    "emmet.syntaxProfiles": {
      "javascript": "jsx"
    },
    "emmet.includeLanguages": {
      "javascript": "javascriptreact"
    },
    "javascript.updateImportsOnFileMove.enabled": "never",
    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
  
    //eslint
    "eslint.autoFixOnSave": true,
    "eslint.validate": [
      {
        "language": "javascript",
        "autoFix": true
      },
      {
        "language": "javascriptreact",
        "autoFix": true
      },
      {
        "language": "typescript",
        "autoFix": true
      },
      {
        "language": "typescriptreact",
        "autoFix": true
      }
    ]
  }
```
### .editorconfig
```
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
```
