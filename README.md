[![lroguet/rpi-nginx-proxy](https://img.shields.io/docker/pulls/lroguet/rpi-nginx-proxy.svg)](https://hub.docker.com/r/lroguet/rpi-nginx-proxy/)
[![lroguet/rpi-nginx-proxy](https://images.microbadger.com/badges/version/lroguet/rpi-nginx-proxy.svg)](https://hub.docker.com/r/lroguet/rpi-nginx-proxy/) [![lroguet/rpi-nginx-proxy](https://images.microbadger.com/badges/image/lroguet/rpi-nginx-proxy.svg)](https://hub.docker.com/r/lroguet/rpi-nginx-proxy/)

# NGINX reverse proxy Docker image for Raspberry Pi

## Description
lroguet/rpi-nginx-proxy sets up a container running NGINX and [docker-gen](https://github.com/jwilder/docker-gen). docker-gen generates reverse proxy configurations for NGINX and reloads NGINX when containers are started and stopped. lroguet/rpi-nginx-proxy is a **Raspberry Pi** compatible version of [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy).

See [Nginx reverse proxy, Docker and a Raspberry Pi](https://fourteenislands.io/2016/04/nginx-reverse-proxy-docker-and-a-raspberry-pi/) for a more detailed explanation.

## Usage
```
$ docker run -d -p 80:80 -v /var/run/docker.sock:/tmp/docker.sock:ro lroguet/rpi-nginx-proxy
```

## Show some love
If you find `lroguet/rpi-nginx-proxy` useful please consider making a donation.

Bitcoin (BTC). `1JU59RHfmdEZCPgetf3rjrWU8JQiFeGPaL`   
Ethereum (ETH). `0x5BbaAb38Be768F281Bc08Ee380735FC5C8cc5CD0`

## Links
* [Docker Hub](https://hub.docker.com/r/lroguet/rpi-nginx-proxy/)
* [In action](https://fourteenislands.io/2016/04/nginx-reverse-proxy-docker-and-a-raspberry-pi/)
