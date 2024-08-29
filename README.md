# vs-code-settings.json

```json
{
  "workbench.sideBar.location": "right",
  "workbench.editor.wrapTabs": true,
  "workbench.colorTheme": "Material Theme",
  "editor.fontFamily": "FiraCode-Retina",
  "editor.fontLigatures": true,
  "editor.minimap.enabled": false,
  "editor.minimap.maxColumn": 100,
  "editor.cursorWidth": 3,
  "editor.tabSize": 4,
  "editor.detectIndentation": false,
  "editor.insertSpaces": true,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.wordWrap": "on",
  "editor.wordWrapColumn": 400,
  "editor.wordSeparators": "`~!@#$%^&*()=+[{]}\\|;:'\",.<>/?",
  "editor.accessibilitySupport": "off",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "php.validate.enable": false,
  "php.suggest.basic": false,
  "git.enabled": true,
  "git.autofetch": true,
  "git.ignoreRebaseWarning": true,
  "scm.showHistoryGraph": false,
  "breadcrumbs.enabled": false,
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "diffEditor.ignoreTrimWhitespace": true,
  "html.format.wrapLineLength": 0,
  "html.format.wrapAttributes": "auto",
  "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
  "intelephense.telemetry.enabled": false,
  "intelephense.files.exclude": [
      "**/.git/**",
      "**/node_modules/**",
      "**/vendor/unitedprofile/**",
      "sites/**/packages/**"
  ],
  "files.watcherExclude": {
      "**/.git/**/*": true,
      "**/node_modules/**/*": true,
      "**/vendor/unitedprofile/**/*": true,
      "sites/**/packages/**/*": true,
      "packages/**/vendor/unitedprofile/**/*": true
  },
  "search.exclude": {
      "**/node_modules": true,
      "**/bower_components": true,
      "**/*.code-search": true,
      "**/node_modules/**/*": true,
      "**/vendor/unitedprofile/**/*": true,
      "sites/**/packages/**/*": true,
      "packages/**/vendor/unitedprofile/**/*": true
  },
  "emmet.includeLanguages": {
      "javascript": "javascriptreact",
      "vue-html": "html",
      "razor": "html",
      "plaintext": "jade",
      "php": "html",
      "twig": "html",
      "blade": "html",
      "vue": "html"
  },
  "[html]": {
      "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascript]": {
      "files.encoding": "utf8",
      "editor.tabSize": 2
  },
  "[yaml]": {
      "files.encoding": "utf8",
      "editor.tabSize": 2
  },
  "[json]": {
      "files.encoding": "utf8",
      "editor.tabSize": 2,
      "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
      "files.encoding": "utf8"
  },
  "[vue]": {
      "editor.defaultFormatter": "octref.vetur",
      "files.encoding": "utf8",
      "editor.tabSize": 2
  },
  "[php]": {
      "editor.defaultFormatter": "junstyle.php-cs-fixer",
      "files.eol": "\n",
      "files.encoding": "iso88591"
  },
  "terminal.integrated.env.osx": {
      "FIG_NEW_SESSION": "1"
  },
  "github.copilot.editor.enableAutoCompletions": true
}


```
