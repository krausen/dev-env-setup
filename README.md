# dev-env-setup
Set up a development machine with this Ansible playbook

## Prerequisites
  - Python >= 2
  - MacOS >= 10.15
  - Signed in to Mac App Store

## How to?

From a clean environment download this [repo](https://github.com/krausen/dev-env-setup/archive/master.zip).

Install pip

```shell

easy_install pip
```

Install ansible

```shell
sudo pip install Ansible
```

**Note!**
Sudo is necessary for Ansible to be installed globally, I have not been able to get it working without it.

Run Ansible playbook (Make sure that you are signed in to Mac App Store)

```zsh
ansible-playbook dev-env.yml
```

You can also use tags to set up the environment specifically for Python
```zsh
ansible-playbook dev-env.yml --tags python
```
