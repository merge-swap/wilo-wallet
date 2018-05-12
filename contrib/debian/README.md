
Debian
====================
This directory contains files used to package wilod/wilo-qt
for Debian-based Linux systems. If you compile wilod/wilo-qt yourself, there are some useful files here.

## wilo: URI support ##


wilo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wilo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wiloqt binary to `/usr/bin`
and the `../../share/pixmaps/wilo128.png` to `/usr/share/pixmaps`

wilo-qt.protocol (KDE)

