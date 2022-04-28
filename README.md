# XForms_FIXED_2022_04_28
Date : 28/04/2022

The current XForms lib package for Linux Mint 20.04 / Ubuntu 20.04
has a bug that cayses a crash when clicking in any menu.
It is based on XForms 1.2.3, when the stable version is 1.2.4
(and is since 2014...)

I suspect that is follows some recent changes in the X11 libraries.

Precompiled .deb packages for Linux Mint are provided here.
(Should work with all Ubuntu derivatives)

To recompile from source, with the provided patch :
The patchfile is : xforms-1.2.4.X11-FIX.patth ch

Download the source for version 1.2.4
http://download.savannah.nongnu.org/releases/xforms/xforms.latest_stable.tar.gz

Uncompress this archive. You  should get a new directory : xforms-1.2.4 
Copy the file xforms-1.2.4.X11-FIX.patch in the xforms-1.2.4 directory.
In tnis directory, (from a shell), execute :
```
patch -s -p0 < xforms-1.2.4.X11-FIX.patch
```
Then follow XForms the build instructions.

----------
Direct link to the useful files :
Binary files, XForms WISIWIG editor fdesigner :libforms-bin

https://github.com/pmxy/XForms_FIXED_2022_04_28/blob/master/libforms-bin_1.2.4-1ubuntu1_amd64.deb


Development and lib files : libforms-dev

https://github.com/pmxy/XForms_FIXED_2022_04_28/blob/master/libforms-dev_1.2.4-1ubuntu1_amd64.deb


OpenGL extension : libformsgl-dev

https://github.com/pmxy/XForms_FIXED_2022_04_28/blob/master/libformsgl-dev_1.2.4-1ubuntu1_amd64.deb


Documentation : libforms-doc

https://github.com/pmxy/XForms_FIXED_2022_04_28/blob/master/libforms-doc_1.2.4-1ubuntu1_all.deb



