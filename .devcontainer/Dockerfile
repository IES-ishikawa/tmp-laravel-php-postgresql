FROM mcr.microsoft.com/devcontainers/php:1-8.2-bullseye

RUN apt-get update && apt-get -y install libpq-dev && docker-php-ext-install pdo_pgsql
