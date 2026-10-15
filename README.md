# vs_set

'''
{
    // "extensions.autoUpdate": "off",
    // "gitlens.ai.model": "vscode",
    // "gitlens.ai.vscode.model": "copilot:gpt-4.1",
    // "workbench.colorTheme": "GitHub Dark Colorblind (Beta)",
    // "git.blame.editorDecoration.enabled": true,
    // "git.blame.statusBarItem.enabled": false

    "editor.definitionLinkOpensInPeek": false,
    "ruby.intellisense": "rubyLocate",
    "ruby.useLanguageServer": true,
    "solargraph.definitions": true,
    "solargraph.diagnostics": true,
    "solargraph.useBundler": false,
    "terminal.integrated.enableMultiLinePasteWarning": false,
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "cSpell.enabledFileTypes": {
        "css": true,
        "html": true,
        "javascript": true,
        "typescript": true,
        "typescriptreact": true,
        "json": true,
        "less": true,
        "markdown": true,
        "plaintext": true,
        "scss": true,
        "text": true,
        "ruby": true,
        "php": true,
        "yaml": true,
        "yml": true
    },
    "[ruby]": {
        "editor.defaultFormatter": "Shopify.ruby-lsp",
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.tabSize": 2,
        "editor.insertSpaces": true,
        "files.trimTrailingWhitespace": true,
        "files.insertFinalNewline": true,
        "files.trimFinalNewlines": true,
        "editor.rulers": [
            120
        ],
        "editor.semanticHighlighting.enabled": true
    },
    "rubyLsp.rubyVersionManager": {
        "identifier": "rbenv"
    },
    "rubyLsp.formatter": "auto",
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.formatOnSave": true
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.formatOnSave": true
    },
    "redhat.telemetry.enabled": false,
    "plantuml.commandArgs": [
        "-Xmx2g",
        "-DPLANTUML_LIMIT_SIZE=16384"
    ],
    "editor.largeFileOptimizations": false,
    "cSpell.userWords": [
        "timeframe",
        "UNNEST",
        "chirashi",
        "chakra",
        "STRUCT",
        "paypay",
        "Paypay"
    ],
    "editor.unicodeHighlight.nonBasicASCII": false,
    "git.openRepositoryInParentFolders": "always",
    "go.testEnvFile": "${workspaceFolder}/.env.test",
    "[php]": {
        "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?"
    },
    "[go]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": "never"
        }
    },
    "diffEditor.ignoreTrimWhitespace": false,
    "terminal.external.osxExec": "Warp.app",
    "workbench.colorCustomizations": {
        "terminal.foreground": "#bbbbbb",
        "terminal.background": "#000000",
        "terminal.ansiBlack": "#4f4f4f",
        "terminal.ansiBlue": "#96cbfe",
        "terminal.ansiCyan": "#c6c5fe",
        "terminal.ansiGreen": "#a8ff60",
        "terminal.ansiMagenta": "#ff73fd",
        "terminal.ansiRed": "#ff6c60",
        "terminal.ansiWhite": "#eeeeee",
        "terminal.ansiYellow": "#ffffb6",
        "terminal.ansiBrightBlack": "#7c7c7c",
        "terminal.ansiBrightBlue": "#b5dcff",
        "terminal.ansiBrightCyan": "#dfdffe",
        "terminal.ansiBrightGreen": "#ceffac",
        "terminal.ansiBrightMagenta": "#ff9cfe",
        "terminal.ansiBrightRed": "#ffb6b0",
        "terminal.ansiBrightWhite": "#ffffff",
        "terminal.ansiBrightYellow": "#ffffcc",
        "terminal.selectionBackground": "#363983",
        "terminalCursor.foreground": "#ffa560"
    },
    // "workbench.iconTheme": "ayu-mirage-zed",
    "cursor.general.disableHttp2": true,
     "workbench.editor.enablePreviewFromQuickOpen": false,
     "workbench.editor.openPositioning": "last",
    "workbench.editor.enablePreview": false,

    // 検索関連
    "search.mode": "reuseEditor",
    "search.searchEditor.focusResultsOnSearch": true,
    "search.searchOnType": false,
    "docker.extension.enableComposeLanguageServer": false,

    // ターミナル関連
    "terminal.integrated.fontFamily": "Hack Nerd Font Mono",
    "terminal.integrated.fontSize": 13,

    // クイックピック関連
    "workbench.colorCustomizations": {
        "quickInput.background": "#000000",
        "quickInput.foreground": "#ffffff",
        "quickInputList.focusBackground": "#555555",
        "quickInputList.focusForeground": "#ffffff",
        "quickInputList.focusIconForeground": "#ffd700",
        "quickInputTitle.background": "#ccc",
        "pickerGroup.foreground": "#66afe9",
        "pickerGroup.border": "#66afe9",
        //  "input.border": "#ffffff",           // QuickPick内の入力欄の枠線
        //  "editor.findMatchBorder": "#ff0000"
        // "widget.shadow": "#ffffff",
        // "editorWidget.border": "#ffffff",
        // "settings.textInputBorder": "#ffffff",
    },
    "[dockercompose]": {
        "editor.insertSpaces": true,
        "editor.tabSize": 2,
        "editor.autoIndent": "advanced",
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "[github-actions-workflow]": {
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "explorer.excludeGitIgnore": true,
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "claudeCode.preferredLocation": "panel",
    "window.autoDetectColorScheme": false,
    "workbench.colorTheme": "GitHub Dark Colorblind (Beta)"   
}

'''


keybind
'''
[
    {
        "key": "ctrl+cmd+[",
        "command": "workbench.action.moveEditorLeftInGroup"
      },
      {
        "key": "ctrl+cmd+]",
        "command": "workbench.action.moveEditorRightInGroup"
      },
      {
        "key": "cmd+k f",
        "command": "workbench.action.closeFolder",
         "when": "workbenchState != 'empty'"
      },
      {
        "key": "ctrl + shift + tab",
        "command": "workbench.action.previousEditorInGroup"
      },
      {
          "key": "cmd+shift+[",
          "command": "-workbench.action.previousEditorInGroup"
      },
      {
          "key": "ctrl + tab",
          "command": "workbench.action.nextEditorInGroup"
      },
      {
          "key": "cmd+shift+]",
          "command": "-workbench.action.nextEditorInGroup"
      },
      {
        "key": "cmd+shift+j",
        "command": "workbench.action.toggleMaximizedPanel"
      },
      {
        "key": "ctrl+shift+1",
        "command": "workbench.action.findInFiles"
      },
      {
        "key": "shift+cmd+f",
        "command": "search.action.openNewEditor"
      },
      {
        "key": "cmd+alt+g",
        "command": "workbench.view.scm"
      },
      {
        "key": "cmd+shift+c",
        "command": "copyRelativeFilePath",
        "when": "editorFocus || explorerViewletVisible"
      }

]
'''
