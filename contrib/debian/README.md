
Debian
====================
This directory contains files used to package RPWNd/RPWN-qt
for Debian-based Linux systems. If you compile RPWNd/RPWN-qt yourself, there are some useful files here.

## RPWN: URI support ##


RPWN-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install RPWN-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your RPWN-qt binary to `/usr/bin`
and the `../../share/pixmaps/RPWN128.png` to `/usr/share/pixmaps`

RPWN-qt.protocol (KDE)

