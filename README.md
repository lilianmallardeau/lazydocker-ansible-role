lazydocker Ansible Role
=======================

An Ansible role that installs [lazydocker](https://github.com/jesseduffield/lazydocker).

Requirements
------------

None

Role Variables
--------------

```yaml
# Directory in which to install lazydocker
lazydocker_install_dir: /usr/local/bin

# Temporary directory used for downloading
lazydocker_tmp_dir: /tmp
```

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: lazydocker
      vars:
        lazydocker_install_dir: /bin
```

License
-------

MIT
