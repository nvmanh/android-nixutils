# Prerequisites #

  * build-essentials
  * this list will be added to


# Setting Up the Toolchain #

  1. Download the GNU/Linux toolchain [here](http://www.codesourcery.com/sgpp/lite/arm/portal/release1293).
  1. Once the download is complete open up terminal and type `chmod 755 /path/to/downloadedfile.bin` followed by `/path/to/downloadedfile.bin` or if it is in your current directory `./downloadedfile.bin`
  1. If it complains about your system using dash instead of bash execute the command `dpkg-reconfigure dash` and select no when prompted.
  1. You should now be in the installer.  Install it as you would any other program to any path you like.  All documents in this project will use `~/android/toolchain/` as the directory to install to.

> Your toolchain should now be set up properly.