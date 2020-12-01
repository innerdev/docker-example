FROM php:8.0.0-cli-alpine
WORKDIR /var/www/php 
COPY . .
CMD ["php", "-S", "0.0.0.0:8000", "src/index.php"]
EXPOSE 8000