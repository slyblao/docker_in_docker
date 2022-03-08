# Docker In Docker 
Run Docker in Docker container using [/var/run/docker.sock]

Build the Dockerfile

docker build -t test-image .

docker exec -it test-image /bin/sh
