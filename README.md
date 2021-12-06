# Dockerized PHP application in Apache

Template of simple PHP web application running in Apache.

### (Re-)Build container

Updates the Composer dependencies:

`./rebuild`

### Run application

`docker-compose up -d`

- `http://localhost:8101`- Application
- `http://localhost:8102`- Adminer
- `http://localhost:8103`- PHP MyAdmin

### Stop application

`docker-compose down`