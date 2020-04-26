# Docker Cheat Sheet

#### [docker ps](https://docs.docker.com/engine/reference/commandline/ps/)
```
$ docker ps 
$ docker ps -a
```

#### [docker start](https://docs.docker.com/engine/reference/commandline/start/)
```
$ docker start [option] [container]
$ docker stop [option] [container]
```

#### [docker run](https://docs.docker.com/engine/reference/run/)
```
$ docker run redis
$ docker run -it redis command
$ docker run -it -p 3000:3000 CONTAINER_ID
```

#### [docker build](https://docs.docker.com/engine/reference/commandline/build/)
```
$ docker build . 
$ docker build -t docker_username/given_name:latest .
$ docker build -f file_name .
```

#### [docker exec](https://docs.docker.com/engine/reference/commandline/exec/)
```
$ docker exec -it 1b37197a2807 redis-cli
```

#### [docker-compose](https://docs.docker.com/compose/)
```
$ docker-compose up --build
$ docker-compose up -d => run in background
$ docker-compose down
$ docker-compose ps

$ docker-compose -f docker-compose-dev.yml up --build
```
