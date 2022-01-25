How to build the package

You must to download the latest source tarball from upstream, you can either do
this manually or using the command: uscan.

Unpack the tarball into this folder.

Apply the patches like this if needed:
patch < debian/patches/fix-installation-script.patch

And finally run: dpkg-builpackage -us -uc -b
