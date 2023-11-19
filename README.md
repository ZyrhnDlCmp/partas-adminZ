Set up

npm i
composer update
Generate key

php artisan key:generate
Reset database

php artisan db:wipe
*Run migrations

php artisan migrate
Seed database

php artisan db:seed
Run project

php artisan serve
npm run dev
Not necessary, just notes
Run tests

vendor\bin\phpunit
Build for production

npm run prod
cp .env.example .env
php artisan config:cache
php artisan route:cache
php artisan optimize
Make model

php artisan make:model Status
php artisan make:migration create_status
Make controller

php artisan make:controller StatusController
