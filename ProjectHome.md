# glog #

**The project is moved to github. Please visit our github page [here](https://github.com/google/glog).**

The glog library implements application-level logging.
This library provides logging APIs based on C++-style streams and
various helper macros.

## NEWS: glog 0.3.3 released ##

This release includes several bug fixes and minor updates. Thanks for people who contributed patches or reported bugs!

  * Add --disable-rtti option for configure.
  * Visual Studio build and test fix.
  * QNX build fix (thanks vanuan).
  * Reduce warnings.
  * Fixed LOG\_SYSRESULT (thanks ukai).
  * FreeBSD build fix (thanks yyanagisawa).
  * Clang build fix.
  * Now users can re-initialize glog after ShutdownGoogleLogging.
  * Color output support by GLOG\_colorlogtostderr (thanks alexs).
  * Now glog's ABI around flags are compatible with gflags.
  * Document mentions how to modify flags from user programs.