
Debian
====================
This directory contains files used to package kaishend/kaishen-qt
for Debian-based Linux systems. If you compile kaishend/kaishen-qt yourself, there are some useful files here.

## kaishen: URI support ##


kaishen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kaishen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kaishenqt binary to `/usr/bin`
and the `../../share/pixmaps/kaishen128.png` to `/usr/share/pixmaps`

kaishen-qt.protocol (KDE)

