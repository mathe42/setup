1. VSCode https://code.visualstudio.com/insiders/
2. PHP https://windows.php.net/download#php-8.2-ts-vs16-x64
3. Fira Code https://fonts.google.com/specimen/Fira+Code
4. Composer https://getcomposer.org/
5. Volta https://volta.sh/
6. volta install node
7. volta install deno
8. volta install pnpm
9. volta install yarn



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
        "getpsalm.psalm-vscode-plugin"
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
    "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', monospace"
}
```
