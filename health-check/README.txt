docker commands

docker build -t health-check:0.1 .
docker run --name health-check -p 8181:8181 health-check:0.1

docker logs <container_id>

docker ps

docker ps -a

docker rm -f <container_id>

docker rmi -f <imageid>

docker images

rm -rf .git*

git init
git branch -M main
