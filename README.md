# laravel-starter-kit
[![styleci](https://styleci.io/repos/67811396/shield)](https://styleci.io/repos/67811396)

Laravel starter kit

If you want develop API, look at
[api](https://github.com/melihovv/laravel-starter-kit/tree/api) branch.

## Changes
- `local_providers`, `local_aliases` and `local_global_middlewares` keys in
`config/app.php`
- `app/User.php` move to `app/Models/User.php`
- `AdditionalMethods` trait for Eloquent models
- sqlite database connection for in-memory tests
- `TestHelpers` trait
- `Hash::setRounds(5)` in `TestCase.php` for tests speed up
- `DatabaseTestCase.php` for really fast tests which use database
- additional helpers
- custom configs for phpmd and phpcs
- abstract FormRequest class
- pre-commit hook which runs php tests, phpmd and phpcs analysis

## Installed packages
- doctrine/dbal
- barryvdh/laravel-ide-helper
- itsgoingd/clockwork
- garygreen/pretty-routes
- illuminated/console-mutex
- rap2hpoutre/laravel-log-viewer
- reliese/laravel
- serafim/properties
- thedevsaddam/laravel-schema

## Things you may do manually
- name of your app in `config/app.php`
- `timezone` in `config/app.php`
- `locale` in `config/app.php`
- enable laravel-plugin in PhpStorm
- enable phpmd and phpcs inspections in PhpStorm
- configure phpunit in PhpStorm
- mark `app` folder as `Sources root` and specify `App` package prefix
