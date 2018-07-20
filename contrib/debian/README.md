
Debian
====================
This directory contains files used to package masterdemod/masterdemo-qt
for Debian-based Linux systems. If you compile masterdemod/masterdemo-qt yourself, there are some useful files here.

## masterdemo: URI support ##


masterdemo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install masterdemo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your masterdemoqt binary to `/usr/bin`
and the `../../share/pixmaps/masterdemo128.png` to `/usr/share/pixmaps`

masterdemo-qt.protocol (KDE)

