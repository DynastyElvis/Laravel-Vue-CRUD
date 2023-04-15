<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## Build app
Laravel CRUD using repositories pattern and vue.js


### Steps
- git clone `https://github.com/OlegMarko/vue-laravel-repositories-crud.git`
- `cd vue-laravel-repositories-crud`
- run command: `composer install`
- run command: `npm install`
- add permissions 777 to ./public ./storage ./bootstrap
- change `.env` file similar to `.env.example`
- run command: `php artisan migrate`
- run command: `php artisan serve`
- set base url to `resources/assets/config.js`
- visit to if your base url `http://localhost:8000` [http://127.0.0.1:8000](http://127.0.0.1:8000)