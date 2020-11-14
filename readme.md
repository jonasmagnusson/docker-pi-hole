# Docker Pihole

This is a small docker image for running [Pi-hole](https://pi-hole.net/).

## Installation

Clone this repository and build the Docker image:

```bash
# Git clone repository
git clone https://github.com/jonasmagnusson/docker-pi-hole.git
```

## Usage

Use the following commands to control the container:

```bash
# Run Docker container
docker-compose up --detach
```

```bash
# Restart Docker container
docker-compose restart
```

```bash
# Stop Docker container
docker-compose down
```

Data is persistent and stored in the folders `data` and `config`.
