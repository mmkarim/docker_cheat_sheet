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
$ docker run -it redis redis-server
```

#### [docker build](https://docs.docker.com/engine/reference/commandline/build/)
```
$ docker build . 
$ docker build -t docker_username/given_name:latest .
```

#### [docker exec](https://docs.docker.com/engine/reference/commandline/exec/)
```
$ docker exec -it 1b37197a2807 redis-cli
```
