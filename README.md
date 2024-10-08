<p align="center"><img src="/art/logo-long.png" alt="Logo Pupuk Kaltim"></p>

# Granule Laravel Shifter

Welcome to Granule Laravel Shifter, a Laravel package that provides a quick way to upgrade your Laravel application to the newer version that using [Granule Starter Kit](https://github.com/pupukkaltim/granule-starter-kit). This package is intended to be used in Laravel applications that are using the [Granule Starter Kit](https://github.com/pupukkaltim/granule-starter-kit) package.

## Minimum System Requirements

| Name     	| Minimum Version 	|
|----------	|-----------------	|
| Laravel  	| > 10.x.x        	|
| PHP      	| > 8.2.x         	|
| Composer 	| > 2.7.x         	|
| Granule Starter Kit 	| > 2.0.x         	|

## Installation

For stable package install using this command to get the latest version. **(RECOMMENDED)**
```bash
composer require granule/laravel-shifter --dev
```

To run the upgrade process, you need to run this command.
```bash
php artisan pkt:upgrade
```

## Full Installation

Before you install granule laravel shifter, you need to setup the composer first. You need to make [Github Personal Access Token](https://github.com/settings/tokens/new?scopes=repo&description=granule-starter-kit) first. If your token **not registered** on your composer, you need to register first using this command.
- To check existing composer config on your device.
```bash
composer config -l
```
1. Register Starter Kit Repository to Project
```bash
# to register it locally on your project
composer config repositories.granule-laravel-shifter vcs https://github.com/pupukkaltim/granule-laravel-shifter.git

# or to register it globally in your device 
composer config --global repositories.granule-laravel-shifter vcs https://github.com/pupukkaltim/granule-laravel-shifter.git
```

2. Install Granule Laravel Shifter
```bash
composer require granule/laravel-shifter --dev
```

## How To Use

1. Make sure your application installed with [Granule Starter Kit](https://github.com/pupukkaltim/granule-starter-kit).
2. Make sure you have committed all your changes before running the command.
3. **(RECOMMENDED)** Make a new branch for the upgrade process to avoid any conflict.
4. Run the command below to upgrade your application.
```bash
php artisan pkt:upgrade
```
1. Check laravel installed version using this command.
```bash
php artisan --version
```
1. After the upgrade process is done, you need to check your application for any error or conflict.


## Authors

- [Sallie Trixie Zebada Mansurina](https://github.com/sallieeky)
