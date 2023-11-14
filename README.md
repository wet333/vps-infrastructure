# Infrastructure Deployment Guide

This document provides a step-by-step guide on how to deploy the infrastructure using Ansible.

## Prerequisites

Ensure you have Ansible installed on your machine. If not, you can install it using the following command:

```bash
sudo apt-get install ansible
```

## Deployment

To deploy the infrastructure, execute the following command:

```bash
sudo ansible-playbook -i inventory.ini deploy-to-vps.yml 
```

Please replace inventory.ini with your inventory file and deploy-to-vps.yml with your playbook file.