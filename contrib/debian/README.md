
Debian
====================
This directory contains files used to package aseand/asean-qt
for Debian-based Linux systems. If you compile aseand/asean-qt yourself, there are some useful files here.

## asean: URI support ##


asean-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install asean-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aseanqt binary to `/usr/bin`
and the `../../share/pixmaps/asean128.png` to `/usr/share/pixmaps`

asean-qt.protocol (KDE)

