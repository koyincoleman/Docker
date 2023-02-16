# Docker

Installing docker:
sudo apt update
sudo apt install docker.io
service docker status
sudo service docket start

Docker...most of the commands go from Docker Client through API to Docker Daemon
Docket host runs the Docker Daemon and Registry

Docker Image is a template of instructions which is used to create containers.
DockerFile is needed to build docker image
From ...base image layer
Docker uses a copy-on-write strategy with both Docker images and docker containers
Share and copy files for better efficiency
Reduces overall disk utilization for better performance

Components of Docker:
Dockey Registry - host and distrubute Doocker images amoungst users

