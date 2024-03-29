* FF (Nightly) https://www.mozilla.org/de/firefox/channel/desktop/
* Edge (Canary) https://www.microsoftedgeinsider.com/de-de/download/canary
* Git https://git-scm.com/download/win
* VSCode https://code.visualstudio.com/insiders/
* PHP https://windows.php.net/download#php-8.2-ts-vs16-x64
* Fira Code https://fonts.google.com/specimen/Fira+Code
* Composer https://getcomposer.org/
* Notepad++ https://notepad-plus-plus.org/downloads/v8.4.8/
* Volta https://volta.sh/ `volta install X` X=node/deno/pnpm/yarn
* Win Subsystem
* Ubuntu for Subsystem https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV?hl=de-de&gl=de
* Docker https://docs.docker.com/desktop/install/windows-install/
* Win Terminal https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=de-de&gl=de
* Nice Shell https://ohmyposh.dev/docs/installation/windows
* Adobe Acrobat Reader https://get.adobe.com/de/reader/
* Zeiterfassung https://app.edtime.de/app


VSCode Settings
.vscode/extensions.json
```json
{
    "recommendations": [
        "formulahendry.auto-rename-tag",
        "wcwhitehead.bootstrap-3-snippets",
        "rifi2k.format-html-in-php",
        "eamodio.gitlens",
        "xdebug.php-debug",
        "neilbrayfield.php-docblocker",
        "bmewburn.vscode-intelephense-client",
        "getpsalm.psalm-vscode-plugin",
        "adam-bender.commit-message-editor",
        "ms-vscode-remote.remote-ssh",
        ""ms-vscode-remote.vscode-remote-extensionpack",
        "ms-azuretools.vscode-docker",
        "ms-vscode-remote.remote-wsl",
        "firefox-devtools.vscode-firefox-debug",
        "spmeesseman.vscode-taskexplorer",
        "wayou.vscode-todo-highlight",
        "chrmarti.regex",
        "alefragnani.Bookmarks",
        "johnpapa.vscode-peacock",
        "MS-vsliveshare.vsliveshare"
    ]
}
```
Config
```json
{
    "workbench.sideBar.location": "right",
    "git.suggestSmartCommit": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "auto-rename-tag.activationOnLanguage": [
        "html",
        "php"
    ],
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 1000,
    "editor.fontLigatures": true,
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', monospace",
    "workbench.settings.openDefaultKeybindings": true,
    "explorer.autoRevealExclude": {
        "**/vendor": true
    },
    "search.exclude": {
        "**/vendor": true
    },
    "debug.console.acceptSuggestionOnEnter": "on",
    "editor.stickyScroll.enabled": true,
    "editor.stickyScroll.maxLineCount": 10,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs":"active"
}
```
