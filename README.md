# docker-php-sample

A simple PHP web application example for [Docker's PHP Language Guide](https://docs.docker.com/language/php/).
Stack: Apache MySQL PHP running on Docker and using Docker Secret Key

## Create a password.txt file
$ echo "example-password" > password.txt

## Run container
$ docker compose up --build

## Refresh db data
$ docker volume rm ${name of volume}

## Delete containers
$ docker compose rm 
