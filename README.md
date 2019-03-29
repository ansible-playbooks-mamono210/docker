This playbook installs docker and docker compose on CentOS7.

## Install docker and docker compose 

Change to root and execute commands below.

```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


