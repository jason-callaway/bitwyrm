bitwyrm
=======

Overview
--------
bitwyrm is a utility for moving bit repositories from the Internet to a disconnected network.  "Who on earth would want to do that?" you ask.  What if you have a secure corporate network with a slow Internet proxy, or no proxy at all?  Want to do Ruby development?  Or Python?  Have fun dealing with dependencies.

For those who frequently find they have plenty of storage on "the inside" but have limited resources on their laptop or jump-host, bitwyrm is here to help.  It can crawl HTTP repositories, or use native cloning tools like rubygems-mirror.

bitwyrm is written in Python, but may leverage many other languages' native tools.

Wyrmholes
---------
bitwyrm supports (or will support -- it's alpha code now) the following target types:
* HTTP
* PyPI
* rubygems.org

bitwyrm will maintain whole mirrors of the targets, or just as much as you specify in MB, GB, TB, etc.

If you're on a traditional jump-host or proxy, your "inside" systems can pull from the local directory.  If your network is a little more disconnected, you can ask bitwyrm to create CD, DVD, or Blu-Ray images.

Usage
-----

