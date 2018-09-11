
Debian
====================
This directory contains files used to package ecopayd/ecopay-qt
for Debian-based Linux systems. If you compile ecopayd/ecopay-qt yourself, there are some useful files here.

## ecopay: URI support ##


ecopay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ecopay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ecopayqt binary to `/usr/bin`
and the `../../share/pixmaps/ecopay128.png` to `/usr/share/pixmaps`

ecopay-qt.protocol (KDE)

