# 0.7.0 (2019-07-21)

* Exposed controls for OpenEXR's worker thread pool.
* Added functions for working with OpenEXR's multiview attribute.
* Fixed nasty bug involving non (0,0) data window origins.  This involved
  adding new functions for handling such cases properly.
* Fixed various bugs involving handling C++ exceptions properly across FFI.

# 0.6.0 (2018-06-15)

* Added support for incremental reading/writing of scanline EXR files.
* Added support for envmap access.
* Changed some parameters to be u32 instead of usize.
* Misc reorganization of the crate.
* Misc bug fixes.
