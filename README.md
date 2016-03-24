Role Name
=========

Installs open-vm-tools if the target machine is a VMWare guest. VMWare fully supports it nowadays:

https://kb.vmware.com/selfservice/microsites/search.do?language=en_US&cmd=displayKC&externalId=2073803

https://blogs.vmware.com/vsphere/2015/09/open-vm-tools-ovt-the-future-of-vmware-tools-for-linux.html

If you instead want to use VMWare tools there are a number of ansible roles doing just that.

Requirements
------------

Role has been developed and tested on CentOS 7, with ansible 1.9.

Role Variables
--------------

None. Everything should work out of the box.

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-open-vm-tools, tags: ['open-vm-tools'] }

License
-------

MPL-2.0

Author Information
------------------

Janne Blomqvist https://github.com/jabl
