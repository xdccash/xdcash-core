
Debian
====================
This directory contains files used to package xdcashd/xdcash-qt
for Debian-based Linux systems. If you compile xdcashd/xdcash-qt yourself, there are some useful files here.

## xdcash: URI support ##


xdcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xdcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xdcashqt binary to `/usr/bin`
and the `../../share/pixmaps/xdcash128.png` to `/usr/share/pixmaps`

xdcash-qt.protocol (KDE)

