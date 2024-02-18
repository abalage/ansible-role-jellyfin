abalage.jellyfin
================

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

  roles:
    - abalage.jellyfin
```

License
-------

GPL-3.0

Author Information
------------------

Created by Balázs NÉMETH (balagetech.com).
