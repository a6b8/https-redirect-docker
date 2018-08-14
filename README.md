# Simple Redirect Docker Image
Redirect all http (80) Request to https (443) with a nginx server

Docker Image Listen to Port: 80

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
    image: a6b8/
```

