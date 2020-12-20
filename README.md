<p align="center">
<img src="https://gblobscdn.gitbook.com/spaces%2F-LBKK1y7h_XWAtuRJG9X%2Favatar.png?alt=media" alt="ElectronJS" width="200"/> 
<img src="https://i.dlpng.com/static/png/94951_preview.png" alt="Plus Icon" width="200"/> 
<img src="https://laravel.com/img/logomark.min.svg" alt="Laravel Logo" width="170"/> 
</p>

:exclamation:  This GitHub repository uses deprecated npm packages

# Electron JS with Laravel
> PHP VERSION: 7.4.11,
>LARAVEL VERSION 8x

## Requirements
- PHP installed on your computer (7.4 or higher)
- [Composer](https://getcomposer.org/download/)
- [Laravel](https://laravel.com/docs/8.x#via-laravel-installer)
- [NodeJs](https://nodejs.org/en/) (Recommended installing the LTS version instead of the current version)
- You will need also NPM (The Node Package Manager comes with the nodejs installation)

## How to Install
- First download this [Laravel with ElectronJS](https://github.com/DevShaded/electron-laravel) Repository
- Then open your terminal and go into the project
- Run command `npm install`
- Then go into the `www` folder
- Run command `php -r "file_exists('.env') || copy('.env.example', '.env');"`
- Run command `composer install -q --no-ansi --no-interaction --no-scripts --no-progress --prefer-dist`
- Run command `php artisan key:generate`

## How to run
- Run Command `npm start electron .` in the root folder not the `www` folder

And you are done!

> Stuck? Message me on Discord! DevShaded#1435 or make an issue in the issue tab!
