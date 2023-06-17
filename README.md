[![Actions Status - Master](https://github.com/juju4/ansible-starbase/workflows/AnsibleCI/badge.svg)](https://github.com/juju4/ansible-starbase/actions?query=branch%3Amaster)
[![Actions Status - Devel](https://github.com/juju4/ansible-starbase/workflows/AnsibleCI/badge.svg?branch=devel)](https://github.com/juju4/ansible-starbase/actions?query=branch%3Adevel)

# starbase ansible role

Setup JupyterOne starbase server, Graph-based security analysis for everyone.
* https://github.com/JupiterOne/starbase
* https://www.austinkelleher.com/starbase/

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 2.14

### Operating systems

Tested on Ubuntu 20.04, 22.04.

## Example Playbook

Just include this role in your list.
For example

```
- host: myhost
  roles:
    - juju4.starbase
```

See also docs folder for example playbooks for Azure and Digital Ocean

## Variables

TBD

## Continuous integration

```
$ pip install molecule docker
$ molecule test
$ MOLECULE_DISTRO=ubuntu:22.04 molecule test --destroy=never
```

## Troubleshooting & Known issues

TBD

## License

BSD 2-clause
