mac_user_add
================

A bash script to create, configure and delete users on Mac OS X 10. Tested on Mac OS X 10.11.

User directories are not cleaned up by this script on deletion.

Example
-------

Create an admin user with real name Kylo Ren and username kylo.

    ⇝ mac_user_add -a -r "Kylo Ren" kylo

Create a user with username automaton.

    ⇝ mac_user_add automaton

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/mac_user_add/blob/master/LICENSE).
