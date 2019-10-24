FROM php:5.6-apache

RUN apt-get update --force-yes -y
RUN apt-get install --force-yes -y curl
RUN apt-get install --force-yes -y php5-curl

RUN a2enmod rewrite
