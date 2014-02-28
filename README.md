YAFT Debian
===========

A debian package build for YAFT.

Build your YAFT source into this directory using the maven.tomcat.home
directive. Modify the debian/control file so you don't depend on the 'sakai'
package, modify the debian/install file so your YAFT artefacts go into the
right place, update debian/changelog to reflect the new version, then run:

debuild --no-lintian -us -uc

YAFT's .deb file will be be built into the directory above this repository
directory.
