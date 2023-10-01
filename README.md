<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel REST API with Sanctum

This is an example of a REST API using auth tokens with Laravel Sanctum


## Usage

1. Clone GitHub repo for this project locally
git clone git@github.com:DevKandil/laravel-sanctum-api.git

2. cd into your project
cd laravel-sanctum-api

3. Install Composer Dependencies
composer install

4. Install NPM Dependencies
npm install

5. Create a copy of your .env file
cp .env.example .env

6. Generate an app encryption key
php artisan key:generate

7. Create an empty database for our application with name laravel-sanctum-api

8. In the .env file, add database information to allow Laravel to connect to the database

9. Migrate the database
php artisan migrate
