mglantz.vsftpd
=========

A test role for molecule / podman testing which only installs the vsftpd server software.

Requirements
------------

For molecule testing, a RHEL 8 server with 
```
podman ansible python3 python3-virtualenv gcc git
```
packages installed.

Role Variables
--------------
None

Dependencies
------------
None

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mglantz.vsftpd }
```

License
-------
GPL 3.0

Author Information
------------------
mglantz
