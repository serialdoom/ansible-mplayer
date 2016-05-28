Mplayer
=========

Install mplayer from sources

Role Variables
--------------

For this roles the following variables can be defined

  - `install_path`: where mplayer will be installed. A full
  directory structure will be created in the form of `install_path`/bin,
  `install_path`/etc, etc.
  - `mplayer_lavdopts_threads`: default number of lavdopts threads to use
  - `mplayer_version`: the version to install.


Example Playbook
----------------

    - hosts: all
      roles: 
        - mplayer


License
-------

BSD
