# docker-laravel-composer
Container for running laravel composer commands, based on the latest official composer, with a few laravel requirements and a couple of database (mysql and postgresql) options installed.

Available on [Docker Hub](https://hub.docker.com/r/tomsowerby/laravel-composer/)

Usage should be the same as the [Official Composer](https://hub.docker.com/r/composer/composer/)

Run composer (command run from a laravel directory):

	docker run -it --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp tomsowerby/laravel-composer


Please report bugs or suggestions for this container to the [GitHub issue](https://github.com/tomsowerby/docker-laravel-composer/issues) page.