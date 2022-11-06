# Customise your VS Code
---
### Mac OS Fonts

1. [Install Fira Code on your device](https://github.com/tonsky/FiraCode)

2. Open VS Code 
3. Hold <button>Ctrl</button> + <button>,</button>
4. Go to __Text Editor__ > __Font__ > __Font Family__
5. Change the font family to __fira code__ 


###  Want to change more!

__To set custom dark theme with minimal product icon pack and different colour for syntax__ follow the steps below - 
1. Press and hold <button>Ctrl</button> + <button>Shift</button> + <button>P</button> to open Command Palette
2. Type <code>Open User Settings (JSON)</code> in search bar, it will open settings.json file
3. Copy and Paste the code below

```
{"tailwindCSS.includeLanguages": {
    "html": "html",
    "javascript": "javascript",
    "css": "css"
},
"editor.suggestSelection":{
    "string": true 
},
"editor.mouseWheelZoom": true,
"workbench.editor.untitled.hint": "hidden",
"liveServer.settings.donotShowInfoMsg": true,
"security.workspace.trust.untrustedFiles": "open",
"files.autoSave": "afterDelay",
"explorer.confirmDelete": false,
"code-runner.runInTerminal": true,
"[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
},
"[css]": {
    "editor.defaultFormatter": "vscode.css-language-features"
},
"[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
},
"window.autoDetectColorScheme": true,
"zenMode.fullScreen": false,
"explorer.confirmDragAndDrop": false,
"json.schemas": [

],
"editor.fontFamily": "fira code",
"editor.fontLigatures": true,
"workbench.activityBar.iconClickBehavior": "focus",
"workbench.editor.autoLockGroups": {
    "terminalEditor": false
},
"explorer.fileNesting.expand": false,
"liveServer.settings.donotVerifyTags": true,
"terminal.external.linuxExec": "gitbash",
"git.autofetch": true,
"codetour.showMarkers": false,
"blockman.n01LineHeight": 0,
"workbench.colorCustomizations": {
    "activityBar.activeBackground": "#181417",
    "activityBar.activeBorder": "#eed03c",
    "activityBar.background": "#181417", 
    "activityBar.foreground": "#eed03c",
    "activityBar.inactiveForeground": "#a0a0a0", //icon color
    "activityBarBadge.background": "#ff0000",
    "activityBarBadge.foreground": "#b3323b",
    "sash.hoverBorder": "#f3c356",
     "statusBar.background": "#181417",
    "statusBar.foreground": "#e7e7e7",
    "statusBarItem.hoverBackground": "#ff3333",
    "statusBarItem.remoteBackground": "#8400ff",
    "statusBarItem.remoteForeground": "#e7e7e7",


    "titleBar.activeBackground": "#181417",
    "titleBar.activeForeground": "#e7e7e7",
    "titleBar.inactiveBackground": "#8400ff",
    "titleBar.inactiveForeground": "#e7e7e7",
    "editor.lineHighlightBackground": "#1073cf2d",
    "editor.lineHighlightBorder": "#68f5ff1f"
},
"editor.wordWrap": "off",
"diffEditor.wordWrap": "on",
"editor.guides.indentation": false,
"editor.guides.bracketPairs": false,
"editor.inlayHints.enabled": false,
"better-comments.highlightPlainText": true,
"editor.cursorStyle": "block-outline",
"liveServer.settings.mount": [

],
"workbench.colorTheme": "Bear Theme",
"workbench.iconTheme": "eq-material-theme-icons",
"terminal.integrated.tabs.defaultColor": "terminal.ansiMagenta",
"workbench.productIconTheme": "el-vsc-v1-icons",
"window.zoomLevel": 1,
}

```
> Note: You may need to install extra extensions listed below to make it work properly

| For     | Extension Name | 
| :---        |    :----:   |  
| Font Colour      | [Bear Theme]( https://marketplace.visualstudio.com/items?itemName=dahong.theme-bear)       | 
| File Icon Theme  | [Material Theme Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme-icons)   | 
| Product Icon Theme | [Minimalist Product Icon Theme](https://marketplace.visualstudio.com/items?itemName=ElAnandKumar.el-vsc-product-icon-theme) |



---
Feel free to contribut your custom theme and settings ideas. 
