FROM php:8.0-fpm-buster

COPY php.ini /user/local/etc/php/

RUN apt update
RUN apt install -y wget git unzip libpq-dev vim gnupg2

# Set env
ENV COMPOSER_ALLOW_SUPERUSER=1

COPY ./php-fpm.d/zzz-www.conf /usr/local/etc/php-fpm.d/zzz-www.conf

WORKDIR /var/www

ENV PATH $PATH:/root/.composer/vendor/bin
