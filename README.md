## get it up and running.

After you clone this project, do the following:

```bash
# go into the project
cd Vue-Laravel-SPA

# create a .env file
cp .env.example .env

# install composer dependencies
composer update

# install npm dependencies
npm install

# generate a key for your application
php artisan key:generate

# generate Server secret for JWT
php artisan jwt:secret

#php artisan migrate

........
