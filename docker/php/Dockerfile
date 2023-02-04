FROM php:8.1.15-fpm-alpine3.17

RUN apk update && apk add \
    unzip \
    git \
    openssl \
    libxml2-dev \
    postgresql-dev

RUN docker-php-ext-install \
    bcmath \
    xml \
    pdo_mysql

RUN rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

WORKDIR /var/www/
