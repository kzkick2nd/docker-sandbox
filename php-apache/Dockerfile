FROM php:7.2.21-apache-buster
RUN sed -i "s/80/8080/g" /etc/apache2/sites-available/000-default.conf /etc/apache2/ports.conf
USER www-data
WORKDIR /var/www/html/
COPY ./ ./
