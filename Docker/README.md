# WordPress-React - Docker

## Building & Running
The docker container will be built with the rest of the container, there is no need to pre-build the container.  
In order to run the container stack, use the following command in the `Docker/` folder: `docker-compose -f docker-compose.dev.yml up -d --build`.  

This will create a new Docker stack, containing three containers:
- wordpress - The main PHP environment with the WordPress website.
- wordpress-mysql - The MySQL database for the docker container.
- wordpress-react - The react frontend, for easier development.

