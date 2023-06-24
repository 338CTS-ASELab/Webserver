# Webserver

This Repo serves as the static webpage that routes students and instructors to the various pages that serve content for documentation and training.

## Features

- 💾 PHP
- 💾 Apache

## Setup

This repo is utilizing a Docker container to serve the content. You will need to ensure you have the requisites to create a docker container.

```sh
# Download the files from the repo
git clone git@github.com:338CTS-ASELab/Webserver.git

# Navigate into the folder
cd webserver

# Create the docker containers
sudo docker-compose up -d
```
