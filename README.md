# VS Code Pitch Black Red Color Theme

All backgrounds and unnecessary borders are black. Syntax highlighting colors are taken from the [Monocolor Red Atom Theme](https://github.com/Cerealkillerway/atom-monocolor-red-syntax-theme) (default) theme.


## Install and activate

1. Install: `ctrl+p` (or `cmd+p`), enter `ext install pitch black red`.
2. Activate: `ctrl+k, ctrl+t` (or `cmd+k, cmd+t`), select `Pitch Black Red`.


## Settings

Some features cannot be enabled automatically by this extension. In the user settings, set the following.

- Remove highlighting of tab lines etc: `"workbench.colorCustomizations": { "editorWhitespace.foreground": "#000" }`
- Remove line next to scroll bar: `"editor.overviewRulerBorder": false`
- Black title bar: `"window.titleBarStyle": "custom"`


## Manual Install

```
cd ~/.vscode/extensions
git clone https://github.com/ambyjkl/vscode-pitch-black-theme.git pitch-black-red-theme
```
