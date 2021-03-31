# Ansible Collection - bonddim.linux

[![Galaxy version](https://img.shields.io/badge/dynamic/json?style=flat&label=galaxy&logo=ansible&url=https://galaxy.ansible.com/api/v2/collections/bonddim/linux/&query=latest_version.version)](https://galaxy.ansible.com/bonddim/linux)
[![Licence](https://img.shields.io/github/license/bonddim/ansible-collection-linux?logo=license)](https://github.com/bonddim/ansible-collection-linux/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/bonddim/ansible-collection-linux?logo=github)](https://github.com/bonddim/ansible-collection-linux/commits/main)


## Tested with Ansible
Tested with the stable releases of Ansible 2.9 and 2.10 and the development version of Ansible


## Dependencies
```yaml
collections:
  - name: community.general
  - name: community.docker
```


## Included content
Roles
| FQDN Name | Documentation | Build Status |
| --------- | :-----------: | :----------: |
| bonddim.linux.lxd | [Readme](https://github.com/bonddim/ansible-collection-linux/blob/main/roles/lxd/README.md) | [![](https://img.shields.io/github/workflow/status/bonddim/ansible-collection-linux/lxd/main?logo=github)](https://github.com/bonddim/ansible-collection-linux/actions/workflows/role_lxd.yaml?query=branch%3Amain) |
| bonddim.linux.snapd | [Readme](https://github.com/bonddim/ansible-collection-linux/blob/main/roles/snapd/README.md) | [![](https://img.shields.io/github/workflow/status/bonddim/ansible-collection-linux/snapd/main?logo=github)](https://github.com/bonddim/ansible-collection-linux/actions/workflows/role_snapd.yaml?query=branch%3Amain) |
| bonddim.linux.docker | [Readme](https://github.com/bonddim/ansible-collection-linux/blob/main/roles/docker/README.md) | [![](https://img.shields.io/github/workflow/status/bonddim/ansible-collection-linux/docker/main?logo=github)](https://github.com/bonddim/ansible-collection-linux/actions/workflows/role_docker.yaml?query=branch%3Amain) |
| bonddim.linux.traefik | [Readme](https://github.com/bonddim/ansible-collection-linux/blob/main/roles/traefik/README.md) | [![](https://img.shields.io/github/workflow/status/bonddim/ansible-collection-linux/traefik/main?logo=github)](https://github.com/bonddim/ansible-collection-linux/actions/workflows/role_traefik.yaml?query=branch%3Amain) |


## Using this collection
Before using the General community collection, you need to install the collection with the `ansible-galaxy` CLI:
```bash
ansible-galaxy collection install bonddim.linux
```

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:
```yaml
collections:
  - bonddim.linux
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.


## Contributing to this collection
If you want to develop new content for this collection or improve what is already here, please open an issue or create a PR

You can find more information in the [developer guide for collections](https://docs.ansible.com/ansible/devel/dev_guide/developing_collections.html#contributing-to-collections), and in the [Ansible Community Guide](https://docs.ansible.com/ansible/latest/community/index.html).


## More information
- [Ansible Collection overview](https://github.com/ansible-collections/overview)
- [Ansible User guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)


## Licensing
GNU General Public License v3.0 or later

See [LICENSE](https://github.com/bonddim/ansible-collection-linux/blob/main/LICENSE) to see the full text.