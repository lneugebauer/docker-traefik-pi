# docker-traefik-pi

**Installation**

```shell
$ cd /opt/
$ git pull git@github.com:lneugebauer/docker-traefik-pi.git
$ cd docker-traefik-pi/
$ cp .env.dist .env
$ vim .env 
$ docker compose up -d
```

**Migration**

Existing data can be migrated by copying the `appdata` directory and `.env` file.
