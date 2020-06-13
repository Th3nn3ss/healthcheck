FROM ubuntu:18.04
MAINTAINER Dennis Chukwunta <chuksmcdennis@yahoo.com>

RUN apt-get update -y
FROM php:7.0-apache

RUN rm -rf /var/www/html/*
ADD . /var/www/html/


CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
