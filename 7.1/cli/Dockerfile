FROM php:7.1-cli

RUN apt-get update \
 && apt-get -y install git libpq-dev mysql-client unzip \
 && docker-php-ext-install bcmath mbstring pdo_mysql pdo_pgsql \
 && curl -sS https://getcomposer.org/installer \
    | php -- --install-dir=/usr/local/bin --filename=composer