# vscodeでiTerm likeなワークベンチ切り替え・タブ切り替えを行う

Menu Bar > Code > Preferences > Keybords Shortcuts
keybindings.json


- Cmd + 1 ~ 9: 現フォーカス中のワークベンチでタブ切り替え
- Cmd + [: 一つ前のワークベンチにフォーカス
- Cmd + ]: 一つ後のワークベンチにフォーカス

```
// Place your key bindings in this file to override the defaults
[
  { "key": "cmd+1", "command": "workbench.action.openEditorAtIndex1" },
  { "key": "cmd+2", "command": "workbench.action.openEditorAtIndex2" },
  { "key": "cmd+3", "command": "workbench.action.openEditorAtIndex3" },
  { "key": "cmd+4", "command": "workbench.action.openEditorAtIndex4" },
  { "key": "cmd+5", "command": "workbench.action.openEditorAtIndex5" },
  { "key": "cmd+6", "command": "workbench.action.openEditorAtIndex6" },
  { "key": "cmd+7", "command": "workbench.action.openEditorAtIndex7" },
  { "key": "cmd+8", "command": "workbench.action.openEditorAtIndex8" },
  { "key": "cmd+9", "command": "workbench.action.openEditorAtIndex9" },
  { "key": "cmd+[", "command": "workbench.action.focusPreviousGroup" },
  { "key": "cmd+]", "command": "workbench.action.focusNextGroup" }
]

```
