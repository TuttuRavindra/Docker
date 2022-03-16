# Docker
1.Install Docker 


# Docker Commands
1.docker version -> Returns the information of server and the client (If we are getting both the client and server response values then we can say that the Docker is working properly)

2.docker info -> Returns more information about the system off docker like how much containers are running(Basically properties command for docker)

3.docker ->returns all the docker commands that can be used and referred to.

4.docker container run --publish 80:80 nginx
docker container run --publish 80:80 --name enakonda nginx
docker container run --publish 80:80 --detach nginx
docker container stop (container ID)
docker container ls 
docker container logs enakonda
docker container top enakonda
docker container --help
docker container rm -f
docker ps
docker container inspect
docker container stats
docker container run it
docker container exec -it
docker container port enakonda
