Ansible Role: Yandex Disk cli
=============================

[![Build Status](https://github.com/webarchitect609/ansible-role-yandex-disk-cli/actions/workflows/build.yml/badge.svg)](https://github.com/webarchitect609/ansible-role-yandex-disk-cli/actions/workflows/build.yml)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-yandex-disk-cli?sort=semver)](https://github.com/webarchitect609/ansible-role-yandex-disk-cli/releases)
[![Downloads](https://img.shields.io/ansible/role/d/30623)](https://galaxy.ansible.com/ui/standalone/roles/webarchitect609/yandex_disk_cli)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-yandex-disk-cli)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/ui/standalone/namespaces/7493/)

Installs [Yandex Disk cli](https://yandex.ru/support/disk-desktop-linux/#cli-gui) from the official repository.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: webarchitect609.yandex_disk_cli }
```

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
