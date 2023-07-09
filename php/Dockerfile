FROM php:fpm-alpine

# Installing dependencies for the PHP modules
RUN apk update 
RUN apk add zip libzip-dev libpng-dev 

# Installing additional PHP modules
RUN docker-php-ext-install mysqli pdo pdo_mysql gd zip