# ansible-system_repo_proxy

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_repo_proxy-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_repo_proxy)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_repo_proxy.svg)](https://github.com/lotusnoir/ansible-system_repo_proxy/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_repo_proxy?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56933)](https://galaxy.ansible.com/lotusnoir/system_repo_proxy)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56933)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure proxy on repository

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_repo_proxy
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_repo_proxy


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

