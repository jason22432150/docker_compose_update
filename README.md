# docker_compose_update
docker compose update

Here is docker compose official Github website
https://github.com/docker/compose

# step1:
```sh
which docker-compose
```
we get 

/usr/bin/docker-compose

# step2:
```sh
$sudo rm /usr/bin/docker-compose
```

# step3:
2022/01/19
https://github.com/docker/compose
the last version is v2.2.3
```sh
curl -L https://github.com/docker/compose/releases/download/v2.2.3/docker-compose-`uname -s`-`uname -m` -o /usr/bin/docker-compose
```

# step4:
```sh
chmod +x /usr/bin/docker-compose
```
