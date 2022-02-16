
Debian
====================
This directory contains files used to package bontecoind/bontecoin-qt
for Debian-based Linux systems. If you compile bontecoind/bontecoin-qt yourself, there are some useful files here.

## bontecoin: URI support ##


bontecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bontecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bontecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bontecoin128.png` to `/usr/share/pixmaps`

bontecoin-qt.protocol (KDE)

