# Laravel-Vue Standard Structure

> A Laravel-Vue Standard Structure.

<p align="center">
<img src="https://i.imgur.com/NHFTsGt.png">
</p>

## Features

-   Laravel 5.7
-   Vue + VueRouter + Vuex + VueI18n + ESlint
-   Pages with dynamic import and custom layouts
-   Login, register and password reset
-   Authentication with JWT
-   Socialite integration
-   Bootstrap 4 + Font Awesome 5

## Installation

-   `composer create-project --prefer-dist cretueusebiu/laravel-vue-spa`
-   Edit `.env` and set your database connection details
-   (When installed via git clone or download, run `php artisan key:generate` and `php artisan jwt:secret`)
-   `php artisan migrate`
-   `npm install` or `yarn`

## Usage

#### Development

```bash
# build and watch
npm run watch

# serve with hot reloading
npm run hot
```

#### Production

```bash
npm run production
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.
