abalage.jellyfin
================

[![CI](https://github.com/abalage/ansible-role-jellyfin/workflows/CI/badge.svg)](https://github.com/abalage/ansible-role-jellyfin/actions?query=workflow%3ACI)

Installs Jellyfin as a generic amd64 package on Linux.

Requirements
------------

None

Role Variables
--------------
Available variables are listed below, along with default values (see defaults/main.yml):

```yaml
jellyfin_user: jellyfin
jellyfin_home: "/opt/jellyfin"
jellyfin_version: 10.8.13
ffpmeg_dir: "/usr/bin"
jellyfin_autostart: true
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  become: true

  roles:
    - abalage.jellyfin
```

License
-------

GPL-3.0

Author Information
------------------

Created by Balázs NÉMETH (balagetech.com).

Workflow code is inspired by Jeff Geerling's amazing work (https://github.com/geerlingguy/).
