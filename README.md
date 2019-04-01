# libwebp for PHP on Windows

## Building

* start the respective Visual Studio console

* `cd` into the directory

* `nmake /f Makefile.vc CFG=release-static RTLIBCFG=static OBJDIR=output`  
  `nmake /f Makefile.vc CFG=debug-static RTLIBCFG=static OBJDIR=output`

Find the build in output\\\*-static\x??\
