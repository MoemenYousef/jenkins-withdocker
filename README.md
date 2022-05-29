# Jenkins CI with Docker binaries installed

docker build -t jenk-with-docker .

docker run -d -p 8081:8080 -v /var/run/docker.sock:/var/run/docker.sock jenk-with-docker
