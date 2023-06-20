# PHP base image
FROM php:8.2-fpm-alpine

# Install dependencies
RUN docker-php-ext-install mysqli pdo_mysql

# Set working directory
WORKDIR /var/www/html

# Expose port 9000 and start php-fpm server
EXPOSE 9000