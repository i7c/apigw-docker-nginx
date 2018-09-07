Simple static reverse proxy on docker
=====================================

A docker compose file and template file for an nginx server config is enough to
build a stupid/basic reverse proxy running in docker.

Define as many `location {}` sections in the template as you want. You can use
variables with the `${var}` syntax. All used variables must be defined in the
docker compose file.

Deployment
==========

To deploy, simply run `docker-compose -f docker-compose.yml up -d` and your
simplistic reverse proxy should be up and running.

