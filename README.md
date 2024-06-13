# my_1st_dockerhub_image

## How to build this image
First, clone the repo
```bash
git clone https://github.com/sanchpet/my_1st_dockerhub_image.git
```
Then switch the directory and build from `Dockerfile`, I suggest to use tags:
```bash
cd my_1st_dockerhub_image.git
docker build -t sanchpet/my_1st_dockerhub_image:v1.1 .
```
Then push it (run `docker login` if you are not logged in Docker Hub):
```bash
docker push sanchpet/my_1st_dockerhub_image:v1.1
```
[Image on DockerHub](https://hub.docker.com/repository/docker/sanchpet/my_1st_dockerhub_image/general)
