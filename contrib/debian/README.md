
Debian
====================
This directory contains files used to package worthlessd/worthless-qt
for Debian-based Linux systems. If you compile worthlessd/worthless-qt yourself, there are some useful files here.

## worthless: URI support ##


worthless-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install worthless-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your worthlessqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

worthless-qt.protocol (KDE)

