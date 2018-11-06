
Debian
====================
This directory contains files used to package proxynoded/proxynode-qt
for Debian-based Linux systems. If you compile proxynoded/proxynode-qt yourself, there are some useful files here.

## proxynode: URI support ##


proxynode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install proxynode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your proxynodeqt binary to `/usr/bin`
and the `../../share/pixmaps/proxynode128.png` to `/usr/share/pixmaps`

proxynode-qt.protocol (KDE)

