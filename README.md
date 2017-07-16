# My-VSCode-Config
My current VSCode settings, extensions and key binding

## Extensions
**Angular 2+ Snippets- Typescript<br />
Auto Rename Tag<br />
IntelliSense for CSS class names<br />
Node TDD<br />
One Dark Pro<br />
Suissize<br />
Terminal Tabs<br />
TypeScript Hero**

## Settings
````
{
    "telemetry.enableTelemetry": false,
    "telemetry.enableCrashReporter": false,
    "[javascript]": {
        
    },
    "editor.tabSize": 2,
    "editor.fontSize": 13,
    "editor.fontFamily": "'Fira Code','Consolas','Droid Sans Mono', 'Courier New', 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "window.menuBarVisibility": "default",
    "editor.renderWhitespace": "none",
    "editor.renderControlCharacters": false,
    "workbench.activityBar.visible": true,
    "workbench.colorTheme": "One Dark Pro",
    "typescript.check.tscVersion": false
}
````

## Key Bindings
````
// Place your key bindings in this file to overwrite the defaults
[
  {
    "key": "ctrl+alt+s",
    "command": "workbench.action.files.saveAs"
  },
  {
    "key": "ctrl+shift+s",
    "command": "workbench.action.files.saveAll"
  },
  {
    "key": "ctrl+f4",
    "command": "workbench.action.closeActiveEditor"
  },
  {
    "key": "ctrl+w",
    "command": "-workbench.action.closeActiveEditor"
  },
  {
    "key": "ctrl+down",
    "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+down",
    "command": "-editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+up",
    "command": "editor.action.copyLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+up",
    "command": "-editor.action.copyLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+i",
    "command": "editor.action.formatDocument",
    "when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+i",
    "command": "-editor.action.formatDocument",
    "when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly"
  },
  {
    "key": "alt+i",
    "command": "typescriptHero.resolve.addImportUnderCursor",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+alt+i",
    "command": "-typescriptHero.resolve.addImportUnderCursor",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+alt+i",
    "command": "typescriptHero.resolve.addMissingImports",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+alt+i",
    "command": "-typescriptHero.resolve.addMissingImports",
    "when": "editorTextFocus"
  },
  {
    "key": "alt+o",
    "command": "typescriptHero.resolve.addImport",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+i",
    "command": "-typescriptHero.resolve.addImport",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+alt+'",
    "command": "workbench.action.terminal.new"
  },
  {
    "key": "ctrl+alt+2",
    "command": "workbench.action.terminal.focusNext"
  },
  {
    "key": "ctrl+alt+1",
    "command": "workbench.action.terminal.focusPrevious"
  },
  {
    "key": "ctrl+alt+4",
    "command": "workbench.action.terminal.kill"
  }
]
````
