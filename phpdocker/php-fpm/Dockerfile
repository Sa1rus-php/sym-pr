FROM phpdockerio/php:8.1-fpm
WORKDIR "/application"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        php8.1-gmagick \ 
        php8.1-imagick \ 
        php8.1-mysql \ 
        php8.1-psr \ 
        php8.1-redis \ 
        php8.1-xdebug \ 
        php8.1-yaml; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
