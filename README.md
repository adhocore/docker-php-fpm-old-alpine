# docker-php-fpm-old-alpine

Offical [docker-php](https://github.com/docker-library/php) no longer builds images for latest PHP versions on top of old alpine 3.13 and 3.14. So this repo is aimed to fill that gap.

All the images are tagged on the name `adhocore/php`.

## Tags and versions

Image Tag     | PHP Version | Alpine Version
--------------|-------------|---------------
8.1-alpine3.13   | 8.1.10      | 3.13
8.0-alpine3.13   | 8.0.10      | 3.13
7.4-alpine3.13   | 7.4.30      | 3.13

8.1-alpine3.14   | 8.1.10      | 3.14
8.0-alpine3.14   | 8.0.10      | 3.14
7.4-alpine3.14   | 7.4.30      | 3.14

## Usage

```sh
docker pull adhocore/php:8.1-alpine3.13

docker pull adhocore/php:8.0-alpine3.14
```

### Credits

The dockerfiles are all copied over from offical [repo](https://github.com/docker-library/php) and only slightly adjusted for alpine base and user group (`www-data`).
