Intel PRO/Wireless 3945 and WiFi Link 4965 devices
==================================================

iwl3945 and iwl4965 are modules produced by the iwlegacy Linux kernel driver,
supporting Intel 3945ABG/BG and 4965AGN wireless LAN devices. These devices
were formerly supported by the iwlwifi driver (iwl3945 and iwlagn modules)
until Linux 2.6.39.1 Supported devices are listed at the end of this page.

[https://wiki.debian.org/iwlegacy](https://wiki.debian.org/iwlegacy)

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: webservers
      gather_facts: yes
      sudo: yes

    roles:
        - ansible-debian-intel-3945-4965-wifi

License
-------

MIT

Author Information
------------------

Has an old Acer Aspire 5920G which needed this.
