# Docker Databases Compose Stack


A single stack for running multiple databases in docker containers.

# run it
````bash
docker-compose up -d
````

# How to connect to mongodb container
````bash
docker exec -it mongodb bash
````

# How to connect to mongodb server in mode admin
````bash
mongo admin -u root -p root
````

# How to connect to mongodb testdb database
````bash
mongo -u mongodb -p mongodb --authenticationDatabase testdb
````

