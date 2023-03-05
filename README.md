# ubuntu-docker
how to prepare docker environment

## Installing Docker

+ [How To Install and Use Docker on Ubuntu 22.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04)

## Check docker service

```bash
sudo systemctl status docker
```

## User

```bash
sudo usermod -aG docker ${USER}
```

```bash
su - ${USER}
```

## Installing Docker Compose

+ [How To Install and Use Docker Compose on Ubuntu 22.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-22-04)
