# WMPD - WordPress+MySql+PhpMyAdmin Docker Compose over TSL

WMPD is docker based server with WordPress, mysql and phpmyadmin all of that over TSL(HTTPS) and Let's encrypt Certificate! 

With this project you can quickly run the following:

- [WordPress](https://hub.docker.com/_/wordpress/)
- [phpMyAdmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
- [MySQL](https://hub.docker.com/_/mysql/)

Contents:

- [Requirements](#requirements)
- [Configuration](#configuration)
- [Installation](#installation)
- [Usage](#usage)

## Requirements

* Make sure you have the latest versions of **Docker** and **Docker Compose** installed on your machine.
* Clone this repository or copy the files from this repository into a new folder.

## Configuration

* Update the the .env file according to your configuration(domains,db user/passwords,admin mail).


## Installation

Run this command inside the project folder:

```
docker-compose up -d
```
## Removing services

To stop and remove all the containers use the`down` command:

```
docker-compose down
```
