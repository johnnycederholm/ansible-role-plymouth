Plymouth
=========

Installs and configures Plymouth with specified theme.

Example Playbook
----------------

    - hosts: desktop
      roles:
         - plymouth
      vars:
        theme_name: debian-mac-style
        theme_src: "{{ playbook_dir }}/themes/plymouth/{{ theme_name }}.zip"

License
-------

MIT