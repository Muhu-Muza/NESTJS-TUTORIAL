
`1. To start the docker container, use this command below:`

```shell
docker-compose up -d
```

__When used with the `-d` flag at the end, it ensures it runs in the background.__


`2. To start a specific service named dev-db in the docker-compose file with the `-d` flag, use:`

```shell
docker-compose up dev-db -d
```

`3. To list the running docker containers, use:`
```shell
docker ps
```

`4. To stop the docker container, use:`
```shell
docker-compose down dev-db
```

`5. To access the PostgreSQL database, use:`
```shell
docker-compose exec dev-db psql -U postgres
```

`6. To pull images from the docker repository(hub.docker.com) use:`
```shell
docker pull <image name>
```

`7. to create a container from an image, use:`
```shell
docker run -it -d <image name>

```

`To show all the running and exited containers, use:`
```shell
docker ps -a
```

`8. to access the running container`
```shell
docker exec -it <container id> bash
```

`9. stops a running container`
```shell
docker stop <container id>
```

`10. to login to the docker hub repository`
```shell
docker login
```

`11. lists all the locally stored docker images`
```shell
docker images
```

`12. to delete a stopped container.`
```shell
docker rm <container id>
```

`13. to delete an image from local storage.`
```shell
docker rmi <image-id>
```

`14. to build an image from a specified docker file.`
```shell
docker build <path to docker file>
```

`15. To create a new image of an edited container on the local system`
```shell
docker commit <container id> <username/imagename>
```
