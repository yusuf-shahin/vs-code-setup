#  Personal Visual Studio Code (vs-code) setup 🏗️

#### change your user setting.json setup and build the coding experience more easy and enjoyable.... 🤠

### How can you do that as a beginner ❓
- open your vs-code
- go to your *settings.json* file in your vs-code .
- remove all your previous stuff from *settings.json* in your vs-code .
- copy and paste the following codes into your *settings.json* file

 **please install vs-code extensions below.** ⬇️
  
👉 __*settings.json*__ code :- 
```js
{
  "editor.fontSize": 17,
  "files.autoSave": "off",
  "editor.tabSize": 1,
  "editor.wordWrap": "on",
  "terminal.integrated.fontSize": 15,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },

  "emmet.triggerExpansionOnTab": true,
  "editor.minimap.enabled": true,
  "prettier.jsxSingleQuote": true,
  "prettier.semi": true,
  "prettier.singleQuote": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.cursorBlinking": "expand",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "highlight-matching-tag.styles": {
    "opening": {
      "left": {
        "custom": {
          "borderWidth": "0 0 0 1.5px",
          "borderStyle": "solid",
          "borderColor": "yellow",
          "borderRadius": "5px"
        }
      },
      "right": {
        "custom": {
          "borderWidth": "0 1.5px 0 0",
          "borderStyle": "solid",
          "borderColor": "yellow",
          "borderRadius": "5px"
        }
      }
    }
  },
  "markdown-preview-enhanced.previewTheme": "Night Owl (No Italics)",
  // "git.enableSmartCommit": true,
  "markdown.preview.fontSize": 16,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": false,
  "window.zoomLevel": 2,
  "workbench.iconTheme": "vscode-icons",
  "vsicons.presets.foldersAllDefaultIcon": false,
  "workbench.colorTheme": "Night Owl (No Italics)",
  "git.openRepositoryInParentFolders": "never",
  "security.workspace.trust.untrustedFiles": "open",

  "better-comments.multilineComments": true,
  "better-comments.highlightPlainText": true,
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF007F", //! Alart Sign
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#A0DADA", //? Highlighter Sign
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#065C52", //// Unnecessary code and node Sign
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "#",
      "color": "#008080", //# Basic general note Sign
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#8EBF91", //* function note sign
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "_",
      "color": "#737373", //_ corss code sign
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ]
}


```


##### If you want then you can easily change the setup as per your convenience 😄

## Importent vs-code extensions for developer 🥂

- Prettier - Code formatter   🩹
- Auto Rename Tag   ⛓️
- Bracket Pair Color DLW   🌈
- Better Comments   🥦
- Css Peek   🦆
- ES7 React/Redux/GraphQL/React-Native snip   :electron:
- Highlight Matching Tag   🧮
- HTML to CSS autocompletion   🛺
- indent-rainbow   🌈
- MDX   🏳️
- Night Owl (vs-code theme)   🦉
- vscode-icons   🔋
- vscode-styled-components   🤠
- Tailwind CSS IntelliSense   🪓


