
Debian
====================
This directory contains files used to package ariond/arion-qt
for Debian-based Linux systems. If you compile ariond/arion-qt yourself, there are some useful files here.

## arion: URI support ##


arion-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install arion-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your arion-qt binary to `/usr/bin`
and the `../../share/pixmaps/arion128.png` to `/usr/share/pixmaps`

arion-qt.protocol (KDE)

