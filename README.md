# libwebp for PHP on Windows

## Building

* start the respective Visual Studio console

* `cd` into the directory

* `nmake /f Makefile.vc CFG=release-static RTLIBCFG=dynamic OBJDIR=output`  
  `nmake /f Makefile.vc CFG=debug-static RTLIBCFG=dynamic OBJDIR=output`

Find the build in output\\\*-static\x??\
