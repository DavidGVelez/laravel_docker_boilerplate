# Docker Laravel Boilerplate

## How to:

### copy .env.example and rename it to .env

`cp .env.example .env`

### Run & install containers

`docker-compose up -d`

### get inside container ssh

`docker exec -it laravel_app /bin/bash`

### install all dependencies

`composer install`

`exit`

### generate artisan key

`php artisan key:generate`

### Enjoy
