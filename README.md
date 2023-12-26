<p align="center"> <img src="https://user-images.githubusercontent.com/50652676/62451340-ba925480-b78b-11e9-99f0-13a8a9cc0afa.png" width="100" height="100"></p>

# Ansible Role: Metabase

An Ansible role to install and configure Metabase on a target system.

## Table of Contents
- [Role Variables](#Role Variables)
- [Example Playbook](#Example Playbook)
- [License](#license)

## Role Variables

- `metabase_version`    : Specify the Metabase version to install.
- `metabase_install_dir`: Specify the installation directory for Metabase.
- `metabase_user`       : Specify the user for Metabase.
- `metabase_group`      : Specify the group for Metabase.
- `metabase_opt_dir`    : Specify the opt_dir group for Metabase.
- `metabase_data_dir`   : Specify the data_dir for Metabase.
- `metabase_log_dir`    : Specify the log_dir for Metabase.
- `metabase_server_bind`: Specify the server_bind for Metabase.
- `metabase_server_port`: Specify the server_port for Metabase.
- [Add any other configurable variables]

## Dependencies

- [List any dependencies or other roles required by this role]

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: username.ansible-role-metabase, metabase_version: "v0.48.0" }

```
## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/cypik/ansible-role-metabase/blob/master/LICENSE) file for details.
