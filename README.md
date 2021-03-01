# Docker starter

A simplest docker ready template.

## Install

[Docker](https://docs.docker.com/engine/install/)

Additionaly to Docker, on linux systems install [docker-compose](https://docs.docker.com/compose/install/#install-compose-on-linux-systems)

## Use

To build the project at the root of the project run `docker-compose build`.

To run it, `docker-compose up -d`

One-liner would be `docker-compose build; docker-compose up -d`

Two images will be built and two containers spawned. To access basic [go here](http://localhost:81) and here for the [pro page](http://localhost/).

To stop containers run `docker-compose stop`, to stop and remove run `docker-compose down`.

For every of the above command you can append the specific service, e.g. `docker-compose up -d pro` to run onyl pro page. The name of basic service is `basic`.

## Reference

Pro folder is base from open source [forty](https://html5up.net/forty). License in /pro/license.txt