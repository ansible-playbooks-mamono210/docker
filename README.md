[![](https://github.com/ansible-playbooks-centos7/docker/workflows/build/badge.svg)](https://github.com/ansible-playbooks-centos7/docker/actions?query=workflow%3Abuild)

# Ansible Playbook - Docker

## Introduction

This program installs Docker and Docker compose on CentOS7.

## How To install

1. Install Ansible and git

```
sudo yum -y install epel-release git
sudo yum -y install ansible
```

2. Execute playbook as root

```
git clone https://github.com/ansible-playbooks-centos7/docker.git
cd docker
ansible-galaxy install -r roles/requirements.yml -p roles/
ansible-playbook -i localhost, -c local install.yml
```
