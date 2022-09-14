Ansible Role - PGDG Repository
=========

Installs the PostgreSQL Global Development Group (PGDG) repository.

Requirements
------------

none

Role Variables
--------------

URLs to the repository and repo key can be overridden via platform specific variables (see defaults/main.yml). The SUSE pgdg repo has the desired PostgreSQL version in the repo name. Default is 13, but override by changing `pgdg_zypp_repo_pgver`.

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: b00ga.repo_pgdg }

License
-------

MIT

Author Information
------------------

This role was created by Shawn K. O'Shea.
