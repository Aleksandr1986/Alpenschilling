
Debian
====================
This directory contains files used to package alpsd/alps-qt
for Debian-based Linux systems. If you compile alpsd/alps-qt yourself, there are some useful files here.

## alps: URI support ##


alps-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alps-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alps-qt binary to `/usr/bin`
and the `../../share/pixmaps/alps128.png` to `/usr/share/pixmaps`

alps-qt.protocol (KDE)

