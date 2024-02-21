# doto-collection

Ansible roles collection for doto

## Molecule

<https://github.com/ansible-community/molecule-plugins>
https://developer.hashicorp.com/vagrant/docs/provisioning/ansible_common

- molecule.yml
  - platforms:  
    <https://github.com/ansible-community/molecule-docker/blob/legacy/master/molecule_docker/driver.py>

## Vagrant

- `vagrant global-status`
- `vagrant global-status --prune`

## VirtualBox

- `VBoxManage list runningvms`
- `VBoxManage controlvm <uuid> poweroff`
- `VBoxManage unregistervm <uuid> --delete`
