
Debian
====================
This directory contains files used to package bitcoinbrassd/bitcoinbrass-qt
for Debian-based Linux systems. If you compile bitcoinbrassd/bitcoinbrass-qt yourself, there are some useful files here.

## bitcoinbrass: URI support ##


bitcoinbrass-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinbrass-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinbrass-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinbrass128.png` to `/usr/share/pixmaps`

bitcoinbrass-qt.protocol (KDE)

