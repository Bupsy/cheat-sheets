## Basics
- Get system info
  - `docker system info`

## Swarm
- Initiate a Docker Swarm
  - `docker swarm init`
- Initiate a Docker Swarm on a specific IP
  - `docker swarm init --addvertise-addr <IP>`
- List all swarm nodes
  - `docker node ls`
- Get Manager join token
  - `docker swarm join-token manager`
- Get Worker join token
  - `docker swarm join-token worker`

## 
- Get Docker Script
  - [get.docker.com](https://get.docker.com)