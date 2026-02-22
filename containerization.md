## containerization

## How to install docker service
1. sudo systemctl start docker
2. sudo systemctl enable docker

## How to allow non-root user access
1. sudo usermod -aG docker $USER

## How to verify what is running
1. docker ps

## How to view all containers
1. docker ps -a

## How to run a container
1. docker run -d -p 8080:80 {INSERT CONTAINERNAME HERE}