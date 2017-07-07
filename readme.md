# Wordpress Docker Wrapper

## Requirements

* docker
* docker-compose // How to install [Install Docker Compose](https://docs.docker.com/compose/install/)
* free port 80 on machine
* free port 3306 on machine

## Start

Just type in Console:

``` 
./start-local-server.sh
```

## Database

### Connect

* Host: db // yes its just db!
* Port: 3306
* PW: wordpress
* User: wordpress
* DB: wordpress

## Change values?

Go to the `docker-compose.yml` located in `./docker-wordpress/`

## Need Help?

[Docker Docs](https://docs.docker.com/)
[Wordpress Docs](https://codex.wordpress.org/)