# Docker-Lamp-Stack
Docker compose of container to build:
- Nginx (latest)
- Mysql
- PHP

Place this repo folder inside web source code
```bash
git submodule add https://github.com/rahman5147/Docker.git
```

Run container:
```bash
docker-compose up -d nginx mysql phpmyadmin
```

Open browser goto [192.168.99.100](192.168.99.100)
