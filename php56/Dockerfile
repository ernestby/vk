FROM php:5.6.40-fpm

#RUN apt-get update \
#&& docker-php-ext-install pro 

#RUN mv /usr/local/etc/php/php.ini-production /usr/local/etc/php/php.ini

#RUN apt-get update && apt-get install php5.6-mysql -y

RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable pdo_mysql

WORKDIR /var/www