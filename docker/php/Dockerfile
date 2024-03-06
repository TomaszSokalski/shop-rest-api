FROM phpdockerio/php:8.2-fpm
WORKDIR "/var/www"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
    git \
    php8.2-bcmath \
    php8.2-mysql \
    php8.2-oauth \
    php8.2-xdebug \
    php8.2-uuid \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*