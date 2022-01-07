Run only with `Dockerfile`

From main directory

```shell
$ build -t app ./ 
$ docker run -it -p 5000:80 app
```

App will be running in host machine `http://0.0.0.0:5000/`

--- 

Sync remote folder


```
$ rsync -a ./* root@143.198.72.16:/root/poc/fastapi-traeffik
```
