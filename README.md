# versionpkg

In 2005 Arch Linux didn't have any standard methods for building packages from VCS repositories using makepkg.

To begin to address this I added this page to the Arch Linux wiki:

https://wiki.archlinux.org/index.php?title=VCS_package_guidelines&oldid=758

A few days later I created an extremely rudimentary makepkg wrapper that read some custom variables from PKGBUILDs:

"[versionpkg]... allows you to easily update your CVS and SVN packages without having to edit the PKGBUILDS manually to enter the date or revision number."

Similar functionality appeared in makepkg itself shortly after and it wasn't fully replaced until August 2012:

http://allanmcrae.com/2012/08/changes-to-vcs-packaging-support-in-makepkg/
