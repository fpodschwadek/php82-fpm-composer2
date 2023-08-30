# php82-fpm-composer2
Docker Image for PHP-FPM 8.2 with Composer 2.x.

Base image is [php:8.2-fpm](https://hub.docker.com/layers/library/php/8.2-fpm/images/sha256-15d8e89c6513fc0aa9a337a60a1149817056519b6d7d5e1712a9000819fc720e?context=explore) with additional `git`, `unzip`, and `zip` Debian packages installed.

Composer 2.x binary copied from [composer/composer:2-bin](https://hub.docker.com/layers/composer/composer/2-bin/images/sha256-a6a518709735610ef3ca249db8b8941e185fad472a3ec06eaab6038e185ab43f?context=explore).

[Docker image on DockerHub](https://hub.docker.com/repository/docker/fpod/php82-fpm-composer2).

[Dockerfile on GitHub](https://github.com/fpodschwadek/php82-fpm-composer2).
