## Start

config database
npm install
composer install
php artisan migrate
php artisan serve

register:
http://localhost:8000/api/register
raw JSON input: email and password

login:
http://localhost:8000/api/login
raw JSON input:email and password
or via quickey
raw JSON input:email and provider (example: googleLogin)

