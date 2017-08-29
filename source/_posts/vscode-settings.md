---
title: Virsual Studio Code 配置文件
date: 2017-08-28 17:19:27
tags: [vscode, 效率]
categories: 工具
---
这里记录一下我使用`VSCode`的配置文件，方便查阅(不定时更新)。

<!-- more -->

## <strong>配置文件</strong>

```js
// 文件 -> 首选项 -> 设置
{
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Sublime Material Theme - Dark",
    "editor.fontSize": 16,
    "files.exclude": {
        "**/.git": true,
        "**/.svn": true,  //不显示svn文件
        "**/.hg": true,
        "**/CVS": true,
        "**/.DS_Store": true,
        "**/node_modules": true // npm包太多,隐藏目录
    },
    "editor.wordWrap": "on",
    "files.autoSave": "off",
    "editor.tabSize": 2,
    "editor.fontFamily": "Consolas, 'Courier New', monospace",
    "window.zoomLevel": 0,
    "emmet.syntaxProfiles": {
        "vue-html": "html",
        "vue": "html"
    },
    "emmet.includeLanguages": {
        "vue-html": "html",
        "vue": "html"
    },
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "vue"
    ],
    "vetur.format.js.InsertSpaceBeforeFunctionParenthesis": true,
    "javascript.format.insertSpaceBeforeFunctionParenthesis": true
}
```