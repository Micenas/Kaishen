
Debian
====================
This directory contains files used to package gcoind/gcoin-qt
for Debian-based Linux systems. If you compile gcoind/gcoin-qt yourself, there are some useful files here.

## gcoin: URI support ##


gcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/gcoin128.png` to `/usr/share/pixmaps`

gcoin-qt.protocol (KDE)

