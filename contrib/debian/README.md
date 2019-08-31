
Debian
====================
This directory contains files used to package monerotrustd/monerotrust-qt
for Debian-based Linux systems. If you compile monerotrustd/monerotrust-qt yourself, there are some useful files here.

## monerotrust: URI support ##


monerotrust-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install monerotrust-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your monerotrust-qt binary to `/usr/bin`
and the `../../share/pixmaps/monerotrust128.png` to `/usr/share/pixmaps`

monerotrust-qt.protocol (KDE)

