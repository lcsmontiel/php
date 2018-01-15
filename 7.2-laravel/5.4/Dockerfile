FROM alpine:3.7
LABEL "maintainer Lucas Montiel <lucas.montiel@smartnx.com>"

RUN apk add --upgrade --no-cache supervisor \
    nginx \
    php7 \
    php7-fpm \
    php7-pdo \
    php7-pdo_mysql \
    php7-mysqlnd \
    php7-gd \
    php7-tokenizer \
    php7-xml \
    php7-xmlrpc \
    php7-curl \
    php7-intl \
    php7-pgsql \
    php7-mbstring \
    php7-json \
    php7-ctype \
    php7-memcached \
    php7-oauth \
    php7-mcrypt \
    php7-phar \
    php7-dom && \
    rm -rf /var/cache/apk/*