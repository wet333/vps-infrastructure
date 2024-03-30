# Infrastructure Deployment Guide

This document provides a step-by-step guide on how to deploy the infrastructure using Ansible.

## Prerequisites

Make sure you have Ansible installed on your machine. Additionally, if you plan to authenticate via 
SSH using a username and password (currently default), you'll need to install sshpass.

```bash
sudo apt install ansible
sudo apt install sshpass
```

## Configurations

- Make a copy of dotenv_example.txt and rename it to .env, then replace with correct values
- Rename inventory_example.yml to inventory.yml, and again, replace with the correct values.
- Run the command below...

## Deployment

To deploy the infrastructure, execute the following command:

```bash
sudo ansible-playbook -i inventory.yml deploy-to-vps.yml
```