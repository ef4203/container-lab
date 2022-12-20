# container-lab
A collection of Dockerfiles and compose files for my home lab.


## Installing Podman

Podman will be used for containerization, so you can follow these instruction
to install Podman on your Fedora/RHEL based Linux distro.

```
sudo dnf -y install podman
sudo dnf -y install podman-compose
```

If you are using some other kind of system, I'm sure the instructions will be
similar and can be found using a search engine of your choosing ;).


## Setup

```
sudo systemctl enable --now podman.socket
```
