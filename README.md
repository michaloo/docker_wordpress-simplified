# Simplified Docker Wordpress image

It's simplified official Wordpress Docker image. It only contains
needed dependencies to run basic Wordpress installation without additional scripts or Wordpress files.

## Installation

`docker pull michaloo/wordpress-simplified`

## Basic usage

Run the Wordpress runtime - it is very simple example, it won't start the database:
```docker run -d -v `pwd`:/var/www/html michaloo/wordpress-simplified```

To have full Wordpress environment run on Docker you might be interested in [Dockerpresso](https://github.com/michaloo/dockerpresso) project.

## Used in

Following project uses this image:

* [michaloo/docker_wp-cli](https://github.com/michaloo/docker_wp-cli)
* [michaloo/dockerpresso-cli](https://github.com/michaloo/dockerpresso-cli)
