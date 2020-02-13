# Supported tags and respective `Dockerfile` links

-	[`latest`] Centos 8 + Apache 2.4 + PHP 7.2

# Info
Based on official [centos 8] (https://hub.docker.com/_/centos/) images with addition of:

- Apache 2.4
- PHP 7.2
- PDO
- MySQL
- Mbstring
- GD
- Pear

# Run
Run this image:

```console
$ docker run --name el8-apache-php \
	-d tglab/centos-apache-php:latest
```
