FROM php:5.6-apache

RUN apt-get update \
    && apt-get install libmcrypt-dev --yes

RUN docker-php-ext-install mcrypt \
    && docker-php-ext-install mysqli pdo pdo_mysql

RUN a2enmod rewrite headers
