# Changelog

## Version 1.0.7 w-i-p

- Removed phpfmt PHP formatter, deprecated as of 2019 and no longer useful with PHP 8
- Removed Psalm, we (as most Laravel codebases we know) moved to PHPStan and Larastan
- Removed PHP Symbols, it is now fully replaced by Intelephense
- Replaced felixfbecker.php-debug with its successor xdebug.php-debug
- Improved docs, updated logo

### Todo

- Add PHPStan (swordev.phpstan) - https://marketplace.visualstudio.com/items?itemName=swordev.phpstan&ssr=false#review-details
  - Or https://marketplace.visualstudio.com/items?itemName=ddarkonen.phpstan-larastan
  - https://marketplace.visualstudio.com/items?itemName=SanderRonde.phpstan-vscode
  - https://marketplace.visualstudio.com/items?itemName=calsmurf2904.vscode-phpstan
  - https://marketplace.visualstudio.com/items?itemName=calsmurf2904.vscode-phpstan
- Add Livewire Switcher - https://marketplace.visualstudio.com/items?itemName=bebo925.livewire-switcher
- Add Laravel Pint - https://marketplace.visualstudio.com/items?itemName=open-southeners.laravel-pint
- Add Laravel Pint and PHPStan Alternatives to recommendations
  - https://marketplace.visualstudio.com/items?itemName=msamgan.laravel-pint-vscode
  - https://marketplace.visualstudio.com/items?itemName=raullg97.laravel-pint-linter
- Add Pest Snippets - https://marketplace.visualstudio.com/items?itemName=dansysanalyst.pest-snippets
- Replace Livewire Language Support with https://marketplace.visualstudio.com/items?itemName=haringsbe-haringsrob.laravel-blade-livewire-lsp
- Replace Alpine.js IntelliSense by Adria Wilcynski by its successor by P. Christopher Bowers - https://marketplace.visualstudio.com/items?itemName=pcbowers.alpine-intellisense
- Add https://marketplace.visualstudio.com/items?itemName=DEVSENSE.phptools-vscode, as replacement for other PHP Exts? Need to buy a license? Test it...
- Add laravel-goto-component extension?
- Add Laravel Blade formatter extension?
- Add Laravel Create View extension?
- Add Laravel Blade Wrapper extension?
- Add Alternative Extension Packs
  - https://github.com/onecentlin/laravel-extension-pack-vscode/blob/master/CHANGELOG.md
  - https://marketplace.visualstudio.com/items?itemName=onecentlin.php-productive-pack
- Align code quality with codacy
- Add full docs of all exts

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
