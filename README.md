# create_many_docker_images

![docker-compose and docker](https://jhymer.dev/content/images/2020/05/docker-compose-1.png)

This repo shows a generic example for creating many docker images inside the same repo using docker-compose.

We have the folder `apps` that has 3 app files. We create a docker folder and a docker-compose to handle the files in the docker folder. Inside the docker folder, we put a folder for each app with their requirements and docker image.

## How to create the images

In your bash-like terminal execute the instruction:

`make compose`