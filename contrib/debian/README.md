
Debian
====================
This directory contains files used to package storofwealthd/storofwealth-qt
for Debian-based Linux systems. If you compile storofwealthd/storofwealth-qt yourself, there are some useful files here.

## storofwealth: URI support ##


storofwealth-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install storofwealth-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your storofwealthqt binary to `/usr/bin`
and the `../../share/pixmaps/storofwealth128.png` to `/usr/share/pixmaps`

storofwealth-qt.protocol (KDE)

