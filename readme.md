# Install Laravel

- composer create-project --prefer-dist laravel/laravel LoginLaravel "5.8.*"

- php artisan key:generate --ansi

- php artisan make:auth

# Database Config
### .env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=login
DB_USERNAME=root
DB_PASSWORD=root

# Migrations

- $ php artisan migrate

# Localhost

- $ php artisan serve

# Data Route

- http://localhost:8000/guitarristas