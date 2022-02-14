# syntax=docker/dockerfile:1
FROM php:7-fpm
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
COPY src/ /var/www/html
EXPOSE 80
