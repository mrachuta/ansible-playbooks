## Project name

Ansible playbooks written for my own purposes & training.

## Table of contents
- [Project name](#project-name)
- [Table of contents](#table-of-contents)
- [General info](#general-info)
- [configure-vm](#configure-vm)
- [install-docker](#install-docker)

## General info

Repo contains ansible playbooks used for automate tasks on virtual machines. Often they are supported by shell scritps.

## configure-vm

Playbook used for initial configuration of vm. It realizes following tasks:
- new user creation,
- installing necessary software,
- hardening ssh service,
- personalisation of bash,
- personalisation of ufw (firewall)

## install-docker

Playbook used for installing docker & docker compose with additional customizations:
- adding docker repo,
- installation of docker,
- adding user to docker group,
- installation of docker-compose,
- configuration & start of service