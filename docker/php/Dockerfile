
FROM php:7.4-fpm

RUN apt-get update && apt-get install -y \
    && docker-php-ext-install -j$(nproc) pgsql \
    && docker-php-ext-install -j$(nproc) pdo_pgsql