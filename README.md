# Laravel 5.3 <3 Docker

Run Laravel app inside Docker container.

### How to run

- Clone this repo
- Configure your Laravel app:
    - `cd` to `master` directory
    - Run `composer install`
    - Run `cp .env.example .env`
    - Run `php artisan key:generate`
- Run `docker-composer up -d`
- Open http://localhost:8080 or you can see the phpinfo in http://localhost:8080/info.php