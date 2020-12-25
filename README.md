# docker-apple-silicon
Working simple laravel docker [(preview)](https://docs.docker.com/docker-for-mac/apple-m1/) enviroment for apple silicon

## Images:
* nginx
* php 8.0
* mariaDB (mysql is not supported yet)
* redis

## Usage:
* create db and redis folder under docker-volumes-data folder
* Clone your laravel application under api folder
* docker-compose up --build -d

## Useful commands:
* docker exec -it container_name bash (create bash session inside the container)
