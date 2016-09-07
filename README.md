# Docker Lamp Stack

![](https://www.docker.com/sites/default/files/legal/small_v.png)

Docker compose of container to build:
- Nginx (latest)
- Mysql
- PHP

Place this repo folder inside web source code
```bash
cd <web src directory>
git submodule add https://github.com/rahman5147/docker.git
cd docker
```

Rename file `docker-compose.yml.example` to `docker-compose.yml` & change necessary field ie mysql credintial

Run container:
```bash
docker-compose up -d nginx mysql phpmyadmin
```

Open browser goto [192.168.99.100](192.168.99.100)
>**NOTE:** **To connect to mysql from PHP container need to change `mysql` as host not `localhost` anymore.**