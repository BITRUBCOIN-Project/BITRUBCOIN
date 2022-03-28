
Debian
====================
This directory contains files used to package bitrubcoind/bitrubcoin-qt
for Debian-based Linux systems. If you compile bitrubcoind/bitrubcoin-qt yourself, there are some useful files here.

## bitrubcoin: URI support ##


bitrubcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitrubcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitrubcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitrubcoin128.png` to `/usr/share/pixmaps`

bitrubcoin-qt.protocol (KDE)

