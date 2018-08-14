Docker Hub: [Pre-Build Image](https://hub.docker.com/r/a6b8/redirect-to-https-docker/)

# Simple Redirect Docker Image
Redirect all http (80) Request to https (443) with a nginx server

***The Docker Image use Port:*** 80


## Features
- [x] Redirect http >> https
- [x] Nginx
- [x] Docker
- [x] Docker-Compose
- [x] HA-Proxy Ready
- [x] Rancher (Cattle) Ready

## Quickstart
Docker
```
docker run a6b8/https-redirect-docker
```

Docker-Compose
```
version: '2'
services:
  redirect-to-https:
    image: a6b8/redirect-to-https-docker
```

