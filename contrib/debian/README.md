
Debian
====================
This directory contains files used to package vrcd/vrc-qt
for Debian-based Linux systems. If you compile vrcd/vrc-qt yourself, there are some useful files here.

## vrc: URI support ##


vrc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vrc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vrcqt binary to `/usr/bin`
and the `../../share/pixmaps/vrc128.png` to `/usr/share/pixmaps`

vrc-qt.protocol (KDE)

