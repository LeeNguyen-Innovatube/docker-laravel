mv .env.example .env

composer install

php artisan key:generate

php artisan optimize
