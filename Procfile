release: php artisan migrate --force php artisan db:seed --force
web: vendor/bin/heroku-php-apache2 public/
worker: php artisan queue:listen --tries=3 --timeout=900

