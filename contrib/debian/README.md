
Debian
====================
This directory contains files used to package lavad/lava-qt
for Debian-based Linux systems. If you compile lavad/lava-qt yourself, there are some useful files here.

## lava: URI support ##


lava-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lava-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lavaqt binary to `/usr/bin`
and the `../../share/pixmaps/lava128.png` to `/usr/share/pixmaps`

lava-qt.protocol (KDE)

