# flask-docker

using flask to create an app and Docker to create a container and running it.

docker build -t docker-flask .
docker run --publish 3000:3000 --name docker-flask docker-flask
docker run --name docker-flask -p 3000:3000 -d docker-flask 