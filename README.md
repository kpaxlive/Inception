# Inception

### Description
This project aims to broaden your knowledge of system administration by using Docker. We use WordPress NGINX and mariadb services to up our WordPress website. The main purpose of the project is using docker containers
for each services and make them communicate each other in a VM.

***
### Dependencies
`docker.io` and `docker-compose`


***
### Mandatory part


- A Docker container that contains NGINX with TLSv1.2.
- A Docker container that contains WordPress + php-fpm (installed and configured) only without nginx.
- A Docker container that contains MariaDB only without nginx.
- A volume that contains your WordPress database.
- A second volume that contains your WordPress website files.
- A docker-network that establishes the connection between your containers.
- In the WordPress database, there must be two users, one of them being the administrator.
***
### Diagram of the expected result
![Diagram of the expected result](/structure/docker.png)
