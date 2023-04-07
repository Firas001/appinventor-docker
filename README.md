# App Inventor Dockerized for offline-LAN

This repository contains a ready-to-use Dockerfile to help you build an [AppInventor](https://appinventor.mit.edu) docker image you can run offline in a LAN.

It is based on the Vagrant build process of the official [appinventor-sources](https://github.com/mit-cml/appinventor-sources) repository. It will download that code and its dependencies during the build.

This repository is a modified of [this source](https://gitee.com/better319/appinventor-docker). some files must be manually downloaded from Dockerfile before build it, or uncomment lines

## Building / Running

- Run `docker-compose up` (it will take ~15 minutes for the first build)
- Access it with <http://localhost:8888>
- Login "with Google" and `test@example.com`

## Access Container

- Persistence
- Auto-configuration of rendenzvouz IP

## Connection Debugging
<code>docker exec -it appinventor-appinventorserver-1 /bin/bash</code>


## Instructions
- when connect ai companion with ios app
- use legacy connection preferred use Android Studio as emulator