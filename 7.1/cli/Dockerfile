FROM php:7.1-cli

RUN apt-get update \
 && apt-get -y install git mysql-client unzip \
 && docker-php-ext-install bcmath mbstring pdo_mysql \
 && curl -sS https://getcomposer.org/installer \
    | php -- --install-dir=/usr/local/bin --filename=composer