# docker_course
Course for learning to create fullstasck Dockerfile and configurate them.

## How to run:

1. Install docker and ensure it's configured;

2. Befor building, be sure that you won´t have docker images named app, client or mongo, if so you must change the names in docker-compose.yml files;

3. Run: ```docker build```;

4. Make each image go up separately with:

```
docker-compose up -d mongo
docker-compose up -d app
docker-compose up -d client
```

5. Backend will be running in localhost port 4000 and frontend in port 3000:

```
localhost:4000
localhost:3000
```
