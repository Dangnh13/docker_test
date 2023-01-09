# docker_test

### build image:
 > docker build -t ignore .
 
### build image:
 > docker build -t ignore .

### build image with special file:
 > docker build -t ignore -f Dockerfile.dev .
 
### create container with mount folder
> docker run --name ignore_test -p 8000:3000 -v $(pwd):/usr/src/app   -v /usr/src/app/node_modules ignore

### exec IT
>  docker exec -it ignore_test /bin/sh
