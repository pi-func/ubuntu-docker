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

[Install Docker on Ubuntu 22.04 (with Compose) + 3 Simple Tips | SHB](https://www.smarthomebeginner.com/install-docker-on-ubuntu-22-04/)

https://www.smarthomebeginner.com/install-docker-on-ubuntu-22-04/

[Install the Compose plugin](https://docs.docker.com/compose/install/linux/)

[Install and Configure Docker Compose on Ubuntu 22.04 LTS Jammy](https://www.how2shout.com/linux/install-and-configure-docker-compose-on-ubuntu-22-04-lts-jammy/)


sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin
