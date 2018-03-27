# Docker-nginx
> Start an nginx server that can used as proxy for other nginx containers

## Requirements

### Server

* [Docker](http://docs.docker.com/linux/started/)
* [Docker Compose](https://docs.docker.com/compose/install/)

### How to use
Just make sure that the other nginx containers are up and running.
Do not specify a port in those containers since they will be proxied
by this container.

Also replace the contents in `[]` with the right information

Issue the command below.

```bash
git clone https://github.com/mistaguy/docker-nginx.git
cd docker-nginx

docker-compose up -d

```

## License

This software is licensed under the [MIT license](https://github.com/mistaguy/docker-database/blob/master/LICENSE).

© 2018 Mistaguy