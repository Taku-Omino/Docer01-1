FROM php:7.4-apache

# Apache設定
RUN a2enmod rewrite
COPY ./apache2.conf /etc/apache2/apache2.conf

# PHP設定
COPY ./php.ini /usr/local/etc/php/

# ドキュメントルートにコードをコピー
COPY ./code/ /var/www/html/