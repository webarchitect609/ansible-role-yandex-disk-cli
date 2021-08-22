Ansible Role: Yandex Disk cli
=============================

[![Build Status](https://github.com/webarchitect609/ansible-role-yandex-disk-cli/workflows/build/badge.svg?branch=master)](https://github.com/webarchitect609/ansible-role-yandex-disk-cli/actions?query=workflow%3Abuild)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-yandex-disk-cli?sort=semver)](https://github.com/webarchitect609/ansible-role-yandex-disk-cli/releases)
[![Downloads](https://img.shields.io/ansible/role/d/39614)](https://galaxy.ansible.com/webarchitect609/yandex_disk_cli)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-yandex-disk-cli)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/webarchitect609)

Installs Yandex Disk cli from the official deb repository.

Requirements
------------

None.

Role Variables
--------------

None of the variables need to be altered for installing the latest stable version of the application.
However, all available variables are listed below, along with default values (see `defaults/main.yml`):

    yadisk_cli_package: yandex-disk

Package name to install

    yadisk_cli_deb_source: "deb [arch=amd64] https://repo.yandex.ru/yandex-disk/deb/ stable main"

Repository url.

    yadisk_cli_gpg_key_url: "https://repo.yandex.ru/yandex-disk/YANDEX-DISK-KEY.GPG"

GPG key url.


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.yandex_disk_cli }

License & Author Information
-------
[BSD-3-Clause](LICENSE.md)
