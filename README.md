# doto-collection

Ansible roles collection for doto

## Development

### Environment

`source setup.sh`

### Add a new role

```bash
ansible-galaxy role init roles/<name>
mkdir roles/<name>/molecule
cd roles/<name>/molecule
molecule init scenario
```


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
