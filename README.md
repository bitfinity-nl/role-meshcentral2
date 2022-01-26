# role-meshcentral2
MeshCentral2 is complete remote computer management web site you can download and run in minutes.

Example Playbook
----------------

This is an basic example, how to use the role:

    - hosts: windows_computers

      vars:

      roles:
        - role-meshcentral2



This is an example how to use the role with custom variable(s):

    - hosts: windows_computers
      become: true

      vars:
        # -- custom settings - role-meshcentral2 --
        pkg_repository_type: 'private'

      roles:
        - role-meshcentral2


Source(s)
----------------
* https://www.meshcommander.com/meshcentral2
* https://mangolassi.it/topic/19709/trying-to-switch-meshcentral-from-mongodb-to-nedb/2
* https://github.com/Ylianst/MeshCentral/blob/master/sample-config-advanced.json
