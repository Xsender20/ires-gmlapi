# ir-machine

### Setup github ssh to access it from your server.

- Git: https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04
- Docker: https://docs.docker.com/engine/install/ubuntu/
- Github Setup: https://www.youtube.com/watch?v=X40b9x9BFGo

### Installing Master.

```sh
   git clone git@github.com:elmehdiabdi-src/ir-x.git
```

```sh
   cd ir-x
```

```sh
   sudo docker compose build
```

Note: This command will run all the app.

```sh
   sudo docker compose up -d
```

Now you are ready to use the app.

## Gmail Servers
if you want to use deffirent server in your gmail configuration. do the same tasks bellow on any server and then instead of run all app only run the magic container by runing this command .

```sh
   sudo docker compose build magic && sudo docker compose up -d magic
```

## Expose Ports:

  - 8080
  - 5980
  - 9090
  - 9800
  - 3000

## Update

```sh
    sudo docker compose stop
    git stash
    git pull
    sudo docker compose build
```
