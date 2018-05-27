
Debian
====================
This directory contains files used to package oasisd/oasis-qt
for Debian-based Linux systems. If you compile oasisd/oasis-qt yourself, there are some useful files here.

## oasis: URI support ##


oasis-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install oasis-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your oasisqt binary to `/usr/bin`
and the `../../share/pixmaps/oasis128.png` to `/usr/share/pixmaps`

oasis-qt.protocol (KDE)

