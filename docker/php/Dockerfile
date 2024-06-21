FROM php:8.3.8-apache

RUN apt update && apt install -y $PHPIZE_DEPS && pecl install xdebug && docker-php-ext-enable xdebug