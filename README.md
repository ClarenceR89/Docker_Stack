# Docker.Tech.Stack
## Dockerized Development Environment 

## This solution will create a docker container for each of the following:
- SQL on localhost:41433
- ElasticSearch on localhost:49200
- Kibana on localhost:45601
- Redis on localhost:46379

Run the following command to build the containers:
```
docker-compose build
```

Run the following command to run the containers:
```
docker-compose up -d
```

Run the following command to stop the containers:
```
docker-compose down
```

## Setup Docker
- follow the setup instructions for Docker on your platform https://www.docker.com/get-started

## NOTE - once you have installed Docker and have the docker containers running, 
you will still need to run the DB migrations and seed your DB and Elastic.
