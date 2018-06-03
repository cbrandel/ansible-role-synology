# Role: ansible-role-synology

Role that sets ansible facts for Synology target hosts.

## Requirements
### Ansible version
Ansible 2.4
### Setup module:
The role uses facts gathered by Ansible on the remote host. If you disable the Setup module in your playbook, the role will not work properly.


## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cbrandel.ansible-role-synology }

## License

GPLv3
