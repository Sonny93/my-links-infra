## Create network

First of all, create my-links internal network

> ./create_network.sh

## Create env files

For each sub folder, copy example.env file as .env

/!\ Don't forget to change values in production environment

## Run

Execute each docker-compose files

> docker-compose up -d

## endlessh

- Launch endlessh
- Change the default SSH port `sudo nano /etc/ssh/sshd_config` (ex: Port 29876)
- /!\ Important: Open new terminal and try to connect with the new SSH Port without logout from your first connection
- and voilà!
