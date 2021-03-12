# docker_example
```shell
docker images
docker ps -a
docker pull ubuntu:18.04
docker build -t test_image:18.05 .
docker ps -a
docker rm -vf $(docker ps -a -q)
docker rmi -f $(docker images -a -q)
docker run -i -t test_image:18.05 /bin/bash
docker run test_image:18.05
docker start <container_id>
docker logs <container_id>
docker exec <container_id> <argument>
docker exec -it <container_id> /bin/bash
docker-compose build
docker-compose up
docker-compose logs
```
![image](https://user-images.githubusercontent.com/6627053/110915649-952eda80-8320-11eb-827c-4dbbbf428d70.png)
