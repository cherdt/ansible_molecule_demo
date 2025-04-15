ansible_molecule_demo
=====================

A demo of how to use Molecule to test an Ansible role.

Requirements
------------

Docker (or Podman) should be installed and running.

Python packages (included in `requirements.txt`):

- `molecule-plugins[docker]`

Older versions of Ansible may need `molecule[docker]` instead.

Role Variables
--------------

- application_owner
- application_group
- scripts_path
- application_path


Dependencies
------------

None

Usage
-----

    molecule test
 

License
-------

The Unlicense

Author Information
------------------

Blame cherdt
