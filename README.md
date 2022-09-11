# Kuma-Ansible

This Ansible playbook sets up Nginx, Let's Encrypt, Podman and [Uptime Kuma](https://github.com/louislam/uptime-kuma).

## Requirements

Ansible >= 2.8

## Quick start

- Create a clean RHEL 8 or 9 server
- Run `ansible-galaxy install -r requirements.yaml`
- Run the playbook

## Platforms tested

- Rocky Linux 8.5
- AlmaLinux 9