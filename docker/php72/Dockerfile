FROM php:7.2.31-apache

RUN a2enmod rewrite

RUN docker-php-ext-install mysqli

WORKDIR /var/www/

EXPOSE 80 443 