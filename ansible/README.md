# Ansible
> Ansible is a suite of software tools that enables infrastructure as code. It is open-source and the suite includes software provisioning, configuration management, and application deployment functionality.

[Documentation](https://docs.ansible.com/)

## Install pipx
[pipx docs](https://pipx.pypa.io/stable/)

Install macOS:
```bash
brew install pipx
pipx ensurepath
```

Upgrade macOS:
```bash
brew update && brew upgrade pipx
```

## Install Ansible
Let's see how far we get with ansible core before we need anything more.

Install Ansible core
```bash
pipx install ansible-core
```

Install Ansible
```bash
pipx install --include-deps ansible
```

## Secrets in Ansible
Before starting any secrets in this repo I needed to understand sacure secret keeping in ansible and github.

This is my toughts at the moment that I need to understand more about:
- ansible-vault
    - [Ansible's blogpost](https://www.redhat.com/sysadmin/ansible-playbooks-secrets)
    - [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-use-vault-to-protect-sensitive-ansible-data)
- Sealed Secrets (More kubernetes?)
    - [Bitnami docs](https://docs.bitnami.com/tutorials/sealed-secrets)

