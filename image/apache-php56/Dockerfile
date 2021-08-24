FROM phpstorm/php-56-apache-xdebug-25

RUN apt-get update && apt-get upgrade -y && apt-get -y install libzip-dev zip git  \
	&& a2enmod rewrite \
	&& docker-php-ext-install mysqli \
    && docker-php-ext-install zip


