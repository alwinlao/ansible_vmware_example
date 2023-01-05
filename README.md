# ansible_vmware_lab

The goal of this repo is to deploy an VMware home lab using Inastrastrature as code.

## Requirements

### Ansible Control Node
#### MacOS:
1. Install [Homebrew](https://brew.sh)
2. Install Python
   ```bash
   brew install python@3.10
   ```
3. Install Ansilbe community.general collection
   ```bash
   ansible-galaxy collection install community.general
   ```
4. Run ansible/control_node/requirements.yml

### Vagrant

https://github.com/josenk/vagrant-vmware-esxi
