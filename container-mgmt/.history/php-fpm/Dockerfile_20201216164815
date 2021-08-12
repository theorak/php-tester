FROM php:7.4-fpm-alpine

LABEL maintainer="pierre@piwik.org"

COPY php.ini /usr/local/etc/php/conf.d/php-tester.ini

# WORKDIR is /var/www/html (inherited via "FROM php")
VOLUME /var/www/html

CMD ["php-fpm"]
