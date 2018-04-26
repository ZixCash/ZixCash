
Debian
====================
This directory contains files used to package akulad/akula-qt
for Debian-based Linux systems. If you compile akulad/akula-qt yourself, there are some useful files here.

## akula: URI support ##


akula-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install akula-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your akulaqt binary to `/usr/bin`
and the `../../share/pixmaps/akula128.png` to `/usr/share/pixmaps`

akula-qt.protocol (KDE)

