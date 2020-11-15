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
sudo docker-compose up --detach

# Restart Docker container
sudo docker-compose restart

# Stop Docker container
sudo docker-compose down
```

To change the password while the container is running:

```bash
# Change password
docker exec -it pihole pihole -a -p newpassword
```

Data is persistent and stored in the folder `data`. Make sure to run docker with sudo or change permissions on the data folder accordingly.

