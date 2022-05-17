# demo-docker-compose

simple demo for docker-compose with two services
1. fastapi
2. redis

```bash
$ docker-compose build
$ docker-compose up
```

### reqeust

```
$ curl http://localhost:8000/
"Hello World! I have been seen 10 times.\n"%
```
