
Debian
====================
This directory contains files used to package hedond/hedon-qt
for Debian-based Linux systems. If you compile hedond/hedon-qt yourself, there are some useful files here.

## hedon: URI support ##


hedon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hedon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hedon-qt binary to `/usr/bin`
and the `../../share/pixmaps/hedon128.png` to `/usr/share/pixmaps`

hedon-qt.protocol (KDE)

