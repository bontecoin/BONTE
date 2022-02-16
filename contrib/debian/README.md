
Debian
====================
This directory contains files used to package altecoind/altecoin-qt
for Debian-based Linux systems. If you compile altecoind/altecoin-qt yourself, there are some useful files here.

## altecoin: URI support ##


altecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install altecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your altecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/altecoin128.png` to `/usr/share/pixmaps`

altecoin-qt.protocol (KDE)

