# node-microservice

A simple video streaming app, using node microservices

Build new docker image

> docker build -t node-ms-docker --file Dockerfile .

Run docker image

> docker run -d -p 3000:3000 node-ms-docker

Before pushing to registry (image has to be tagged with registry url)

> docker tag [existing-image] [registry-url]/[image-name]:[version]

> docker-compose down && docker-compose up --build
