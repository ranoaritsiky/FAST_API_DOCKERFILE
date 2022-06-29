# FAST_API_DOCKERFILE
sample app hello world with fastapi with dockerfile
# create image with cmd
docker build -t my_image_fast_api_dockerized .
# run container
docker run -p 80:80  fast_docker_api
# go on adress
0.0.0.0:80
or 
0.0.0.0:80/docs