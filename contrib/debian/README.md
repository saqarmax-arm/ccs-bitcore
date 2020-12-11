
Debian
====================
This directory contains files used to package ccsd/ccs-qt
for Debian-based Linux systems. If you compile ccsd/ccs-qt yourself, there are some useful files here.

## ccs: URI support ##


ccs-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ccs-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ccs-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

ccs-qt.protocol (KDE)

