# Node Nginx With Docker

Simple Setup Nginx HTTP (Only) As Reverse proxy and simple Express Nodejs.

**Used Ports**
 - 80 (As Ingress)
 - 3000 (As Application (Optional))

## Deploying / Running
1. Change `env` file to `.env` and edit them.
2. If you want to see the app as localhost, Uncomment the `port` section in `webapp` service
3. Run `docker-compose up --env-file ./config/.env up` or `docker-compose build` then `docker-compose start` (If want to build)


## Installation

### Required Package/Software

1. Docker and docker-compose (Linux) Docker Desktop (Windows/Mac) Dockstation run Hyper-V (Windows)
2. Nodejs with NPM (Optional for simple app editing)

## Author 

[Restu Wahyu](https://github.com/restuwahyu13)

## Contributor

[Baharsah](https://github.com/baharsah)