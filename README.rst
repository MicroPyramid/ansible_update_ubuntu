Role Name
========

Update Ubuntu

Example Playbook
-------------------------

    - hosts: servers
      remote_user: root
      roles:
         - { role: micropyramid.update_ubuntu , os_release: 12.04_or_15.04_or_14.04 }

License
-------

MIT

Visit our Server Maintenance page `Here`_

.. _Here: https://micropyramid.com/server-maintenance-service/
