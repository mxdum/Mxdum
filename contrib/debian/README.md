
Debian
====================
This directory contains files used to package mxdumd/mxdum-qt
for Debian-based Linux systems. If you compile mxdumd/mxdum-qt yourself, there are some useful files here.

## mxdum: URI support ##


mxdum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mxdum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mxdumqt binary to `/usr/bin`
and the `../../share/pixmaps/mxdum128.png` to `/usr/share/pixmaps`

mxdum-qt.protocol (KDE)

