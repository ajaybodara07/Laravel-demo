# Laravel-demo

## Installation

We need composer to install all packages.

Let's install all packages, by running this command from Terminal

```
composer install
```

Let's do some migration and seed with dummy data.

```
php artisan migrate --seed
```

And run the web server

```
php artisan serve
```

Now, visit http://localhost:8000 to try the demo.

## Notes

This demo use SQLite database by default.
If you want to use another database, you can set configuration in `config/database.php`.
