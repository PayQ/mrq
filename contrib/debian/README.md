
Debian
====================
This directory contains files used to package vrqd/vrq-qt
for Debian-based Linux systems. If you compile vrqd/vrq-qt yourself, there are some useful files here.

## vrq: URI support ##


vrq-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vrq-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vrqqt binary to `/usr/bin`
and the `../../share/pixmaps/vrq128.png` to `/usr/share/pixmaps`

vrq-qt.protocol (KDE)

