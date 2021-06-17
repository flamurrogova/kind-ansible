# kind-ansible

The idea of this repo is to quickly stand up a KIND machine, accompanied by Helm (Kubernetes package manager), kubectl.

[KIND](https://kind.sigs.k8s.io/) (**K**ubernetes **I**n **DO**cker) is a tool to quickly stand up Kubernetes clusters using docker containers as Kubernetes nodes.

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
