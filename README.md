# DSCI 310 IA3 Docker

## DockerHub image
https://hub.docker.com/r/buyangdaffa/dsci310-ia3-buyangdaffa-docker

## Base image
rocker/rstudio:4.4.2

## Added package (pinned)
cowsay 0.8.0

## Features
- Docker image built from rocker/rstudio:4.4.2
- Pinned R package installed using remotes::install_version()
- GitHub Actions automatically builds and pushes to DockerHub