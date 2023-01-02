# Common VS Code Settings
Following are the common VS Code settings:

```json
{
    // Editor Settings
    "editor.mouseWheelZoom": true,
    "editor.multiCursorModifier": "alt", // Other options: "ctrlCmd"
    "editor.rulers": [
        120
    ],
    // Files Settings
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 1000, // "files.autoSave" must be "afterDelay"
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    // Git Settings
    "git.branchProtection": [
        "master",
        "main",
        "stable"
    ],
    "git.terminalGitEditor": false,
    // Window Settings
    "window.autoDetectColorScheme": true,
    // Workbench Settings
    "workbench.tree.indent": 25,
    "workbench.colorTheme": "Solarized Dark", // "window.autoDetectColorScheme" must be enabled
    "workbench.preferredDarkColorTheme": "Solarized Dark", // "window.autoDetectColorScheme" must be enabled
}
```
