Ansibe Role : FileWatch
=======================

This roles acts like a file watcher job.

[![Build Status](https://travis-ci.org/hemanth22/ansible-role-filewatcher.svg?branch=master)](https://travis-ci.org/hemanth22/ansible-role-filewatcher)

Requirements
------------

None.

Role Variables
--------------

**file_watcher_path :** This variable will help to change path address and name of the file to be monitored (By default it will watch the files in the ansible role path under files/ directory).  
**max_run_time:** This variable is to give maximum run time in minutes (default 5 minutes).  

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: hemanth22.filewatcher }

Documentation link: [filewatcher](https://github.com/hemanth22/ansible-role-filewatcher/wiki)  

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by Hemanth BITRA.
