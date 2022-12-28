FROM php:7.4

RUN apt-get update -y && apt-get install -y \
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


CMD ["php-fpm"]