Docker Hub: [Pre-Build Image](https://hub.docker.com/r/a6b8/redirect-to-https-docker/)

# Redirect to https
Redirect all http (80) Request to https (443) with a nginx server

***The Docker Image listen to Port:*** 80


## Features
- [x] Redirect http >> https
- [x] Nginx
- [x] Docker
- [x] Docker-Compose
- [x] HA-Proxy Ready
- [x] Rancher (Cattle) Ready

## Quickstart
### Docker
Make Port 4241 Public (-p),
```
docker run -p 4241:80 a6b8/redirect-to-https-docker
```

### Docker-Compose
```
version: '2'
services:
  redirect-to-https:
    image: a6b8/redirect-to-https-docker
    ports:
      - "4241:80"
```

### HA-Proxy Snippet
```
version: '2'
services:
  redirect-to-https:
    image: a6b8/redirect-to-url-docker
```
