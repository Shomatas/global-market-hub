FROM php:8.3-fpm

RUN apt update
RUN apt upgrade
RUN curl -1sLf 'https://dl.cloudsmith.io/public/symfony/stable/setup.deb.sh' | bash
RUN apt install symfony-cli -y
RUN apt install git -y

WORKDIR /app