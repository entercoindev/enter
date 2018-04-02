
Debian
====================
This directory contains files used to package enterd/enter-qt
for Debian-based Linux systems. If you compile enterd/enter-qt yourself, there are some useful files here.

## enter: URI support ##


enter-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install enter-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your enter-qt binary to `/usr/bin`
and the `../../share/pixmaps/enter128.png` to `/usr/share/pixmaps`

enter-qt.protocol (KDE)

