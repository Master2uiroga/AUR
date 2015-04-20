AUR
===
PKGBUILDs and packages I maintain from my Archlinux User Repository.

# cb-wmhacks
CrunchBang window manager hacks. A Python2 script for adding hot corners and aero style window snapping to a WM o DE. Written for CrunchBang Linux <http://crunchbang.org/> (intended for Openbox) by Philip Newborough and patched for correct Python2 functionality by jpope777.

####About
-----
* Authors:	Philip Newborough (2012) <corenominal@corenominal.org>; jpope777 <jpope@jpope.org>
* License:	WTF Public License
* Website:	http://crunchbang.org/forums/viewtopic.php?id=19180
* Download:	http://packages.crunchbang.org/waldorf/pool/main/cb-wmhacks_0.06_all.deb
* Bug reports:	https://github.com/corenominal/cb-wmhacks/issues
* Source:	git clone https://github.com/corenominal/cb-wmhacks.git
 
####Dependencies
------------
* wmctrl
* python2
* python-xlib
* xdotool (>= 1:2.20110530.1-3)

####Installing
----------
Just extract it and run it locally or move it to your $PATH
>mv cb-hotcorners /usr/bin/cb-hotcorners
>mv cb-aerosnap /usr/bin/cb-aerosnap


# cagraph
A PyGTK widget for ploting charts and graphs using python, gtk and cairo.

####About
-----
* Authors:	Yaacov Zamir (2011) <kobi.zamir@gmail.com>; Nah, Chong Yeol (2011) <nahchongyeol@gmail.com>
* License:	GNU General Public License Version 3
* Website:	https://code.google.com/p/cagraph/
* Download:	https://cagraph.googlecode.com/files/cagraph-1.2.tar.gz
* Bug reports:	https://code.google.com/p/cagraph/issues/list
* Source:	hg clone https://code.google.com/p/cagraph/

####Dependencies
------------
* pygtk
* python-cairo
 
####Installing
----------
Extract it and then run
> python setup.py build
> sudo python setup.py install


