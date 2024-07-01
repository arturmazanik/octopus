# Octopus Learning Platform

An application using [Inertia.js](https://inertiajs.com/) works with [Laravel](https://laravel.com/) and [React](https://reactjs.org/).

## Installation

Clone the repo locally:

```sh
git clone https://github.com/arturmazanik/octopus.git
cd octopus
```

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm install
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

Create an MySQL database.
Run database migrations:

```sh
php artisan migrate
```

Run database seeder:

```sh
php artisan db:seed
```

Run artisan server:

```sh
php artisan serve
```

You're ready to go! [Visit Octopus Learning Platform](https://fiery-octopus.by) in your browser.


## Running tests

To run the Application tests, run:

```
php artisan test
```

## Credits

- Application work by Artur Mazanik (@arturmazanik) and contributors
