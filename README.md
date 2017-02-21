Role Name
=========

This role allows to create, compile and include SELinux modules

Requirements
------------

It requires Development tools (`yum groupinstall "Development tools"`)

Role Variables
--------------

selinux_modules:
  - name: "module1"
    template: "use_only_if_template_name_is_different_than_module_name"

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: MWojtowicz.semodule }

License
-------

MIT
