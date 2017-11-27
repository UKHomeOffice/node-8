# Node 8 Latest
> Node 8 LTS lightweight carbon-alpine. \
> Base image used for spinning up node based apps images/containers

## Installing & getting started

> Run the following steps to get base image available

1) Clone this Repo
2) Run the docker build and run commands
   * `docker build -t node-8 .`
   * `docker run -ti node-8 sh`
3) List the Docker processes to see the container ID of your last running container
   * `docker ps -l`
4) Login to quay.io
   * `docker login quay.io`
5) Commit your docker instance with the ID that you saw running
   * `docker commit <CONTAINER-ID> quay.io/ukhomeofficedigital/node-8`
6) Push the container to quay.io
   * `docker push quay.io/ukhomeofficedigital/node-8`

> This container should then be available for use as the base image
