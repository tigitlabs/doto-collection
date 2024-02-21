virtualbox
=========

Install and configure Oracle VirtualBox.
Based on this instructions:  
<https://www.virtualbox.org/wiki/Linux_Downloads>

Requirements
------------

VirtualBox won't work on a system with Secure Boot enabled, when the modules are not signed.

# <https://askubuntu.com/questions/760671/could-not-load-vboxdrv-after-upgrade-to-ubuntu-16-04-and-i-want-to-keep-secur/768310#768310>

# <https://www.gettoby.com/p/6lva2a9y86ax>

If you have Secure Boot enabled, you can either disable it and set `sign_module` to false.
Or you can sign the modules yourself, and set `sign_module` to true.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
