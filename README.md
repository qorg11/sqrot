# sqrot (SQorgReenshOT)

# What is sqrot?

sqrot is a fork of scrot with removes some useless options and makes
it more usable. Also removes autotools so it's easier to compile.

# Building: 
dependencies:
- giblib
- imlib2
- libtool
- libxcomposite
- libxfixes

To build and install, run the following commands:
```
	$ cd src
    $ make
    # make install
```
To return to original source code you can use '$ make distclean' command.

On Debian systems you can use '# apt install scrot'.

## Author ##

scrot was originally developed by Tom Gilbert under MIT-advertising license.

Currently, source code is maintained by volunteers. Newer versions are
available at
https://github.com/resurrecting-open-source-projects/scrot

sqrot fork is available at https://codeberg.org/qorg11/sqrot
