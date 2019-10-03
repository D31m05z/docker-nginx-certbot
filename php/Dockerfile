FROM php:7-fpm-alpine
LABEL Maintainer="Gergely Boross <sk8geri@gmail.com>" \
      Description="Lightweight container with PHP-FPM 7.3 based on Alpine Linux."

# Install packages
RUN apk --no-cache update
RUN apk --no-cache upgrade
RUN apk --no-cache add libpng-dev postgresql-dev
RUN docker-php-ext-install gd mbstring pdo pdo_mysql pdo_pgsql
