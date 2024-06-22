1. docker pull imageName => to pull image from docker Hub
2. docker run -it imageName => to run container in interactive mode.
3. docker build -t hello-docker => to build an image from dockerfile.
4. docker run hello-docker => to containerize your images.
5. docker images => to list all images.
6. docker run -it hello-docker sh => run docker in shell mode
7. docker container prune => to remove all stopped container
8. docker rm 'withName or Id(id can be first 3 or full id)' => to remove particular container.
9. docker run -p 5173:5173 react-docker => running container with port mapping
10. docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules react-docker => to reflect changes

---

# publishing our images :-

1. docker login
2. docker tag react-docker username/image-name
3. docker push username/image-name

# Docker compose :-

1. Docker init
2. modify your compose.yaml file
3. docker compose up

# Docker compose watch :-

- features :-

1. Sync changes
2. Rebuild
3. Sync-restart

- docker compose watch
