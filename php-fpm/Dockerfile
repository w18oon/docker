FROM php:7.4-fpm
RUN apt-get update \
    && apt-get install --no-install-recommends -y \
    && docker-php-ext-install mysqli \
    && docker-php-ext-install bcmath \