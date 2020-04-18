README
======

This is a backup of the xruna package originally written by [Douglas
McFadzean][1].  The original website appears to have disappeared in the last
year or so, and this script might be useful for others so I'll host it here.

The `PKGBUILD` was reverse-engineered from the similar `PKGBUILD` for `runa` by
the [same author on the AUR][2].  I haven't tested it, but it should put all
the things in the right spots.

The application is licensed under the [Mozilla Public License 2.0
(MPL2)](https://www.mozilla.org/MPL).

xruna
=====

xruna is a leaner (but largely incompatible) fork of the Runa application
launcher, written in Bash. For significant speed gains, it cuts some of the
corners of the XDG freedesktop.org standards. The script runs desktop
applications, optionally opening file and url objects. Objects may be opened
with a specific application or an application selected from a menu of: all
applications; associated applications; or a list of applications read from
stdin. Menus are driven by the dmenu program, and multiple applications may be
selected. xruna can be used as a standalone general-purpose program launcher or
integrated into the context menus of a file manager. It can also replace the
slow standard 'xdg-open' command. Favourite applications can also be
configured. Once installed, execute the command 'man xruna' and see the README
file for more information.


[1]: http://appstogo.mcfadzean.org.uk/linux.html
[2]: https://aur.archlinux.org/packages/runa/
