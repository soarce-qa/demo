FROM php:8.1-apache

MAINTAINER Holger Segnitz <holger@segnitz.net>

RUN pecl install -f -o xdebug
RUN docker-php-ext-enable xdebug.so
