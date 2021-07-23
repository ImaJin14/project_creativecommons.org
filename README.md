## Prerequisites

Make sure you have installed Docker and `docker-compose` for your operating system prior to following these instructions.

## Docker compose

The Docker compose file will start a few required or related services:

- a database server (MySQL or MariaDB)
- a WordPress server
- WordPress CLI - for managing the WordPress instance
- phpMyAdmin - for managing the database


## Environment variables

There are several environment variables required to run the `docker-compose` command. Copy the `.env.example` to `.env` and override the variables if needed. The defaults should work fine.

## Changing database

The `.env` file should contain a variable called `DATABASE` that is used to choose which database to use for development (mysql or mariadb).

If you change the value of the `DATABASE` variable at any time during development, you will need to remove the old database volume in order and rebuild the images to prevent errors. 

1. list all Docker volumes to find the relevant volume
    - `docker volume ls`
2. remove the volume
    - `docker volume rm <volume-id>`
3. rebuild the docker image
    - `docker-compose up --build -d`
