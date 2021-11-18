# Docker Compose for Wordpress Devs #

Docker compose file with php.ini needed for Wordpress Devs on local environment  

### Prerequisite ###

1. Installing Docker:
https://docs.docker.com/install/linux/docker-ce/ubuntu/

2. Installing docker-compose:
https://docs.docker.com/compose/install/


### How to use ###

* Installing and starting containers:
```
docker-compose up -d
```
* Stopping and removing containers:
```
docker-compose down
```
* Wordpress address
```
http://localhost/
```
*PHPMyadmin address
```
http://localhost:8080
```
### Default info ###

```
DB_HOST: db
DB_USER: exampleuser
DB_PASSWORD: examplepass
DB_NAME: exampledb
```