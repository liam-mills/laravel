Installation

- Clone this repo.
- Copy the contents of `.env.example` to a new `.env` file.
- Run the following:

```
yarn install
composer install
php artisan sail:install
php artisan key:generate
./vendor/bin/sail up
```
