# Pritunl Zero + Docker + LinuxServer.io = <3

## Pull the image

    docker pull bashNinja-dockers/docker-pritunlzero

## Run Pritunl

    docker run -d \
        -v {path}:/config \ # MongoDB Data, Logs, Pritunl Zero Config
        -p 9800:443/tcp \
        -p 9799:80/tcp \
        bashNinja-dockers/docker-pritunlzero

## Configure Pritunl

* Open https://youripaddress:9800
* Login with username `pritunl` and password `pritunl`
* Fun
