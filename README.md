# docker_compose_update
docker compose update


If you use 
```sh
docker-compose up 
```
get 
```sh
Version in "./docker-compose.yml" is unsupported. You might be seeing this error because you're using the wrong Compose file version.
```
Then you need to update docker compose 



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
sudo rm /usr/bin/docker-compose
```

# step3:
2022/01/19
https://github.com/docker/compose
the last version is v2.2.3
```sh
sudo curl -L https://github.com/docker/compose/releases/download/v2.2.3/docker-compose-`uname -s`-`uname -m` -o /usr/bin/docker-compose
```

# step4:
```sh
sudo chmod +x /usr/bin/docker-compose
```
