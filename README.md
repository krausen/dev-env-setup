# dev-env-setup
Set up a development machine with this Ansible playbook

## Prerequisites
  - Python >= 2
  - MacOS >= 10.15
  - Signed in to Mac App Store

## How to?

Run Ansible playbook (Make sure that you are signed in to Mac App Store)

```zsh
ansible-playbook dev-env.yml
```

You can also use tags to set up the environment specifically for Python
```zsh
ansible-playbook dev-env.yml --tags python
```
