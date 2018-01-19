Wine Overlay
============
All supported Wine ebuilds from the Gentoo Wine Project
--------------------------------------------------------


Goal
----
Support all Wine ebuilds without bogging down the main Gentoo repository with all of the ebuilds

How to Install
--------------

### repos.conf

Copy wine.conf to /etc/portage/repos/

    wget https://dev.gentoo.org/~np-hardass/proj/wine/wine.conf -O /etc/portage/repos.conf/wine.conf

### Layman

    layman -a wine

### eselect-repository

    eselect repository enable wine

Resources
---------

[Gentoo Wine Project](https://wiki.gentoo.org/wiki/Project:Wine)
