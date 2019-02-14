FROM php:7.0-fpm

RUN apt-get update -y && apt-get install -y libpng-dev libpq-dev

RUN docker-php-ext-install gd
RUN docker-php-ext-install pdo
RUN docker-php-ext-install pdo_pgsql