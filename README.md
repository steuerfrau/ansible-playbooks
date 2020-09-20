Playbook Name
=========
ansible-playbooks

All my Ansible roles as branches in one GIT repository.

Usage
------------
All branches prefixed with "prod" are ready to be used:

```
✘-HUP /srv/ansible-playbooks [prod_skeleton L|✚ 1] 
09:03 $ git branch -v
  master           bad263b Initial commit
  prod_baseinstall 8eeb701 Created from prod_skeleton.
* prod_skeleton    8eeb701 Created from prod_skeleton.
```

The branch "prod_skeleton" contains a basic directory structure und should be checked out to create a branch for a new playbook.

Requirements
------------

Used Roles
--------------

License
-------
GNU General Public License v3.0

Author Information
------------------
Melanie Desaive
m.desaive@mailbox.org
