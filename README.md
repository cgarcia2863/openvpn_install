Ansible Role: openvpn_install
=========

Simple OpenVPN installation following some of the steps found in the openvpn-install.sh script.

Requirements
------------

This playbook only runs in Ubuntu (possibly Debian but untested).

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes
      roles:
         - openvpn_install

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
