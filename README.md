# docker-training

docker container run -d -p 3306:3306 -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker -e POSTGRES_PASSWORD=docker_pwd postgres

docker container run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd mysql

docker container run -d -p 3306:3306 -e MONGO_INITDB_ROOT_USERNAME=docker_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd mongo
