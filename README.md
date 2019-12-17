# nginx-php-fpm-docker

Simple but effective docker-compose setup for using nginx with php-fpm.

# Usage

1. Clone this repo  
`git clone https://github.com/FelixKlauke/nginx-php-fpm-docker.git`
2. Put your code under src
3. Run `docker-compose up -d`
4. Browse your site at `http://<host>:8080`

## Configuration

## Using TLS/SSL

## Info

### PHP Image

We use the `chialab/php:7.3-fpm` image for chialab that contains a lot of common php dependencies. 

### Credits

The basic setup is inspired by [this](http://geekyplatypus.com/dockerise-your-php-application-with-nginx-and-php7-fpm/).