LinuxGSM Ansible role
=========

Ansible role for setting up a LinuxGSM dedicated servers.

Requirements
------------

Linux host capable of handling Ansible (python installed, remote shell access configured).

Role Variables
--------------

There are two important variables:
 * `linuxgsm_gameservers` which is a list of game servers to configure
 * `linuxgsm_gameserver_overrides` which is a map of options for a particular server.

Dependencies
------------

No dependencies at the moment.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: srcds
      vars:
         - srcds_gslt: "Game_Server_Login_Token"
      roles:
         - KarolKozlowski.linuxgsm

License
-------

BSD

Author Information
------------------

Karol Kozlowski
