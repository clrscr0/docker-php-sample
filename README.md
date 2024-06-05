# docker-php-sample

A simple PHP web application example for [Docker's PHP Language Guide](https://docs.docker.com/language/php/).

## Create a password.txt file
$ echo "example-password" > password.txt

## Run container
$ docker compose up --build

## To refresh db data
$ docker volume rm ${name of volume}

## To delete containers
$ docker compose rm 