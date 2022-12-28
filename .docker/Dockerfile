FROM php:7.4

RUN apt-get update -y \
RUN apt-get install -y \
    git \
   zlib \
    json \
    gd \
    pdo \
    imagick \
    pdo_mysql\
    simplexml \
    curl \
    mbstring \


RUN curl --silent --show-error https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

USER 1000