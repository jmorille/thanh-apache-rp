Apache RP 
==========================

## Build de l'image
```bash
$ docker build --rm --name thanh/rp --build-arg http_proxy=${env.http_proxy}  --build-arg https_proxy=${env.https_proxy} --build-arg HTTP_PROXY=${env.http_proxy} --build-arg HTTPS_PROXY=${env.https_proxy}  docker
```



## Lancer l'image
```bash
$ docker run -p 80:80 thanh/rp
```

## Shell sur l'image
```bash
$ docker run -it thanh/rp /bin/bash
```
