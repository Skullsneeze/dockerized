# Dockerized
A traefik docker-compose service

[![Status - WIP](https://img.shields.io/badge/status-WIP-yellow.svg)](https://shields.io/)
[![PR's welcome](https://img.shields.io/badge/PR's-Welcome!-green.svg)](https://shields.io/)
[![MIT license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

## Getting started
- Copy the traefik configuration file
```
cp traefik.yaml.sample traefik.yaml
```
- Update your email in the configuration by replacing `your_name@ydomain.com` with your own email address.

- Create the dockerized docker network
```
docker network create dockerized
``` 

## Run the traefik service
```
docker-compose up -d
```

