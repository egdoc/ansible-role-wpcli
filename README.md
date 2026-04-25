Role Name
=========

Ansible role to install the wp-cli utility on Linux

Requirements
------------

None

Role Variables
--------------

```yaml
wpcli_version: 2.12.0
```
The wp-cli version to install.

```yaml
wpcli_checksum: ce34ddd838f7351d6759068d09793f26755463b4a4610a5a5c0a97b68220d85c
```
Checksum of the default version of wp-cli. Must be changed if version is changed.

```yaml
wpcli_install_dir: /usr/local/bin
```
The system directory in which to install wp-cli.

```yaml
wpcli_repo_url: https://github.com/wp-cli/wp-cli
```
The URL of the official wp-cli repository on GitHub.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: workstations
      roles:
        - role: egdoc.wpcli

License
-------

GPLv2

Author Information
------------------

Created by Egidio Docile.
