# Changelog

## Version 1.0.7

- Remove phpfmt PHP formatter, deprecated as of 2019 and no longer useful with PHP 8
- Remove Psalm, we (and most Laravel codebases we know) moved to PHPStan aka Larastan
- Remove PHP Symbols, it is now fully replaced by Intelephense
- Replace felixfbecker.php-debug with its successor xdebug.php-debug
- Add Laravel Pint VSCode Extension

## Version 1.0.6

- Removed Browser Preview (deprecated), officially replaced by https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server, but we decided not to add any replacement as we do not need this feature anymore using Vite (and hopefully soon Livewire 3)
- Docs

## Version 1.0.5

- Minor improvements, docs

## Version 1.0.4

- Improved docs
- Added Extensions

```
    + ahinkle.laravel-model-snippets
    + austenc.laravel-docs
    + wk-j.save-and-run
    + auchenberg.vscode-browser-preview
    + kamikillerto.vscode-colorize
    + esbenp.prettier-vscode
```

## Version 1.0.3

- Changed PHP Code Formatter

```
    - shevaua.phpcs (abandoned)
    - persoderlind.vscode-phpcbf (abandoned)
    + ValeryanM.vscode-phpsab
```

## Version 1.0.2

- First public version
