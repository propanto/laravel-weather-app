# Laravel Weather App

## Installation

Clone the repo locally:

```sh
git clone https://github.com/propanto/laravel-weather-app.git
cd laravel-weather-app
```

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm i
```

Build assets:

```sh
npm run dev
```

Setup configuration:

```sh
cp .env.example .env
```

Generate application key:

```sh
php artisan key:generate
```

Run database migrations:

```sh
php artisan migrate
```

Run the dev server (the output will give the address):

```sh
php artisan serve
```
