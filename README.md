# My-VSCode-theme-config

### Extension 👇 <br>
Name: GitHub Theme <br>
Id: GitHub.github-vscode-theme <br>
Description: GitHub theme for VS Code <br>
Version: 6.0.0 <br>
Publisher: GitHub <br>
VS Marketplace [Link](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)

### Github Dark Defaul Theme
Open `settings.json` and copy this 👇
```
"editor.tokenColorCustomizations": {
      "comments": "#008800",
      "[GitHub Dark Default]": {
         "types": "#ff0",
         "numbers": "#c4ff00",
         "functions": "#0f0",
         "textMateRules": [
            {
               "scope": "keyword.operator.new",
               "settings": {
                  "foreground": "#ff55ff",
                  "fontStyle": "italic bold"
               }
            },
            {
               "scope": "keyword.operator.arithmetic",
               "settings": {
                  "foreground": "#fff",
                  "fontStyle": "bold"
               }
            },
            {
               "scope": "keyword.operator.assignment",
               "settings": {
                  "foreground": "#fff",
                  "fontStyle": "bold"
               }
            },
            {
               "scope": "keyword.operator.logical",
               "settings": {
                  "foreground": "#fff",
                  "fontStyle": "bold"
               }
            },
            {
               "scope": "keyword.operator.bitwise",
               "settings": {
                  "foreground": "#fff",
                  "fontStyle": "bold"
               }
            },
         ]
      }
   },
```
