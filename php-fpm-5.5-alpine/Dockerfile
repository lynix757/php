FROM php:5.5-fpm-alpine

RUN docker-php-ext-install mysql pdo pdo_mysql \
&& rm -rf /var/cache/apk/*

WORKDIR /var/www/html

EXPOSE 9000

CMD ["php-fpm"]
