# ansible-vps

Install docker on all hosts:

```sh
ansible-playbook playbooks/install_docker.yml --ask-become-pass
```

Create users on all hosts:

```sh
ansible-playbook playbooks/users.yml --ask-become-pass
```
