# kind-ansible

The idea of this repo is to quickly stand up a KIND machine, accompanied with helm, kubectl.

The ansible playbook installs:
- Docker
- KIND
- Helm
- Kubectl

To run this playbook execute:
```
ansible-playbook main.yaml --ask-become-pass --ask-pass
```

Tested on Ubuntu 20.04.
