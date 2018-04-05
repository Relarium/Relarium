
Debian
====================
This directory contains files used to package relariumd/relarium-qt
for Debian-based Linux systems. If you compile relariumd/relarium-qt yourself, there are some useful files here.

## relarium: URI support ##


relarium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install relarium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your relariumqt binary to `/usr/bin`
and the `../../share/pixmaps/relarium128.png` to `/usr/share/pixmaps`

relarium-qt.protocol (KDE)

