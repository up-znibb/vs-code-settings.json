# vs-code-settings.json

```json
{
  // =======================================
  // Global PHP-inställningar
  // =======================================
  "php.validate.enable": false,
  "php.suggest.basic": false,
  "php.validate.executablePath": "/usr/bin/php",

  // =======================================
  // Global Editor-inställningar
  // =======================================
  "editor.accessibilitySupport": "off",
  "editor.cursorWidth": 3,
  "editor.detectIndentation": false,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.insertSpaces": true,
  //"editor.minimap.enabled": false,
  "editor.minimap.maxColumn": 100,
  "editor.tabSize": 4,
  "editor.wordWrap": "on",
  "editor.wordWrapColumn": 400,
  "editor.wordSeparators": "`~!@#$%^&*()=+[{]}\\|;:'\",.<>/?",
  "editor.trimAutoWhitespace": false,

  // =======================================
  // HTML-inställningar
  // =======================================
  "html.format.indentHandlebars": true,
  "html.format.wrapLineLength": 0,
  "html.format.wrapAttributes": "auto",

  // =======================================
  // Fil- och mappinställningar
  // =======================================
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,
  "files.associations": {
    "*.twig": "twig"
  },
  "files.watcherExclude": {
    "**/.git/**/*": true,
    "**/node_modules/**/*": true,
    "**/vendor/unitedprofile/**/*": true,
    "sites/**/packages/**/*": true,
    "packages/**/vendor/unitedprofile/**/*": true
  },

  // =======================================
  // Emmet
  // =======================================
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "vue-html": "html",
    "razor": "html",
    "plaintext": "jade",
    "php": "html",
    "twig": "html",
    "blade": "html"
  },

  // =======================================
  // Git-inställningar
  // =======================================
  "git.enabled": true,
  "git.rebaseWhenSync": false,
  "git.autofetch": true,
  "git.ignoreRebaseWarning": true,
  "git.confirmSync": false,

  // =======================================
  // Intelephense-inställningar
  // =======================================
  "intelephense.telemetry.enabled": false,
  "intelephense.files.maxSize": 9000000,
  "intelephense.maxMemory": 16000,
  "intelephense.trace.server": "messages",
  "intelephense.files.exclude": [
    "**/.git/**",
    "**/node_modules/**",
    "**/.pnpm/**",
    "**/vendor/unitedprofile/**",
    "sites/**/packages/**"
  ],
  "intelephense.stubs": [
    "apache",
    "bcmath",
    "bz2",
    "calendar",
    "com_dotnet",
    "Core",
    "ctype",
    "curl",
    "date",
    "dba",
    "dom",
    "enchant",
    "exif",
    "FFI",
    "fileinfo",
    "filter",
    "fpm",
    "ftp",
    "gd",
    "gettext",
    "gmp",
    "hash",
    "iconv",
    "imap",
    "intl",
    "json",
    "ldap",
    "libxml",
    "mbstring",
    "meta",
    "mysqli",
    "oci8",
    "odbc",
    "openssl",
    "pcntl",
    "pcre",
    "PDO",
    "pgsql",
    "Phar",
    "posix",
    "pspell",
    "readline",
    "Reflection",
    "session",
    "shmop",
    "SimpleXML",
    "snmp",
    "soap",
    "sockets",
    "sodium",
    "SPL",
    "sqlite3",
    "standard",
    "superglobals",
    "sysvmsg",
    "sysvsem",
    "sysvshm",
    "tidy",
    "tokenizer",
    "xml",
    "xmlreader",
    "xmlrpc",
    "xmlwriter",
    "xsl",
    "Zend OPcache",
    "zip",
    "zlib",
    "imagick",
    "random"
  ],

  // =======================================
  // PHP-CS-Fixer-inställningar
  // =======================================
  "php-cs-fixer.onsave": true,
  "php-cs-fixer.formatHtml": false,
  "php-cs-fixer.config": ".php-cs-fixer.php;.php-cs-fixer.dist.php;.php_cs;.php_cs.dist",
  "php-cs-fixer.documentFormattingProvider": true,
  "php-cs-fixer.executablePath": "${workspaceFolder}/vendor/bin/php-cs-fixer",
  "php-cs-fixer.lastDownload": 1733129626411,

  // =======================================
  // Twig-inställningar
  // =======================================
  "twig-language.wrap": 200,
  "twig-language-2.indentStyle": "space",
  "twig-language-2.tabSize": 4,

  // =======================================
  // GitHub Copilot-inställningar
  // =======================================
  "github.copilot.chat.codeGeneration.useInstructionFiles": true,
  "github.copilot.chat.codeGeneration.instructions": [
    { "file": "docs/code-style-php.md" },
    { "file": "docs/code-style-php-pdo.md" },
    { "file": "docs/code-style-js.md" }
  ],
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": false,
    "scminput": false,
    "typescriptreact": false
  },

  // =======================================
  // GitLens-inställningar
  // =======================================
  "gitlens.views.scm.grouped.views": {
    "commits": true,
    "branches": true,
    "remotes": true,
    "stashes": true,
    "tags": true,
    "worktrees": true,
    "contributors": true,
    "repositories": false,
    "searchAndCompare": true,
    "launchpad": false
  },

  // =======================================
  // Explorer-inställningar
  // =======================================
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,

  // =======================================
  // Sök-inställningar
  // =======================================
  "search.useIgnoreFiles": true,
  "search.exclude": {
    "**/*.jpg": true,
    "**/*.png": true,
    "**/*.sql": true,
    "**/*.tar.gz": true,
    "**/*.cache": true,
    "**/*-cache": true,
    "**/.composer": true,
    "**/.config": true,
    "**/.git": true,
    "**/.ssh": true,
    "**/.vim": true,
    "**/.vscode": true,
    "**/OLD*": true,
    "**/antw*": true,
    "**/backup_restore": true,
    "**/bower_components": true,
    "**/cache": true,
    "**/glesys-restore": true,
    "**/goofler.com": true,
    "**/logs": true,
    "**/net.unitedprofile.se*": true,
    "**/node_modules": true,
    "**/old_mysqldumps": true,
    "**/partner*": true,
    "**/productimages*": true,
    "**/sqladmin*": true,
    "**/tmp": true,
    "**/vendor": true,
    "**/.pnpm*": true,
    "sites/**/assets/*": true
  },

  // =======================================
  // Terminal-inställningar
  // =======================================
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },

  // =======================================
  // Workbench- och fönsterinställningar
  // =======================================
  "workbench.sideBar.location": "right",
  "workbench.editor.wrapTabs": true,
  "workbench.colorTheme": "Material Color",
  "workbench.iconTheme": "material-icon-theme",
  "window.confirmSaveUntitledWorkspace": false,

  // =======================================
  // Diff Editor-inställningar
  // =======================================
  "diffEditor.ignoreTrimWhitespace": true,

  // =======================================
  // Breadcrumbs
  // =======================================
  "breadcrumbs.enabled": true,

  // =======================================
  // Språk-specifika inställningar
  // =======================================
  "[html]": {
    "files.encoding": "iso88591",
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "files.encoding": "utf8",
    "editor.tabSize": 2,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "files.encoding": "utf8",
    "editor.tabSize": 2
  },
  "[sql]": {
    "files.encoding": "utf8"
  },
  "[json]": {
    "files.encoding": "utf8",
    "editor.tabSize": 2,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[shellscript]": {
    "files.encoding": "utf8",
    "editor.tabSize": 2
  },
  "[markdown]": {
    "files.encoding": "utf8"
  },
  "[scss]": {
    "files.encoding": "utf8"
  },
  "[twig]": {
    "files.encoding": "iso88591",
    "editor.defaultFormatter": "junstyle.twig-language"
  },
  "[vue]": {
    "files.encoding": "utf8",
    "editor.tabSize": 2,
    "editor.defaultFormatter": "octref.vetur"
  },
  "[php]": {
    "editor.defaultFormatter": "junstyle.php-cs-fixer",
    "files.eol": "\n",
    "files.encoding": "iso88591",
    "editor.insertSpaces": true,
    "editor.rulers": [
      { "column": 120, "color": "#ffffff10" },
      { "column": 170, "color": "#ffffff30" }
    ]
  },
  "[neon]": {
    "files.encoding": "utf8"
  }
}
```
