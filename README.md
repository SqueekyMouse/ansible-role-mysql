MYSQL DB
=========

This role installs mariadb and sets up mysql database.

Requirements
------------

Just make sure apt updated

Role Variables
--------------

db_name, db_user, db_passwd

Dependencies
------------

Python must be installed, not necessary!!

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        db_name: testdb
        db_user: testdbuser
        db_passwd: testdbpasswd
      roles:
         - mysql_db

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
