slock - simple screen locker
============================
simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.

Patches
-------
[Foreground or Background](https://tools.suckless.org/slock/patches/foreground-and-background/)

[DPMS](https://tools.suckless.org/slock/patches/dpms/)

[Control Clear](https://tools.suckless.org/slock/patches/control-clear/)

[Mediakeys](https://tools.suckless.org/slock/patches/mediakeys/) ([modified](https://github.com/Thiago4532/slock/commit/f719720c7e3a4b64f4b21c2c0e3d5c76d2eee0c6))

Customization
-------------
Colors: based on [gruvbox-material](https://github.com/sainnhe/gruvbox-material)
