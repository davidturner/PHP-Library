PHP Library Changes
==================

##Minor Release 1.3.1 December 2012
- Error with `db::join()` varable `$table_a` error.

##Release 1.3 December 2012
- Added new `visitor` class.
   - `visitor::browser()` Will return the visitors browser information
   - `visitor::ip()` Will return visitors IP address
   - `visitor::os()` Will return visitors Operating System title

##Release 1.2 November 2012

- Added table method into html class `html::table()`.
- Updated `db::insert()` to accept multidimension array only values & array for labels.
- Added `video::` class.
   - `video::youtube()` Will parse and return an embed URL for YouTube links
   - `video::vimeo()` Will parse and return an embed URL for Vimeo links
   - `video::embed()` Will embed an iframe onto page for a given embed URL


##Release 1.1 November 2012

A long awaited update to the library system, updates as follow:

- Added FTP support, `ftp::` (alpha tested).
- Updated string encode functions, baseencode -> encode, basedecode -> decode.
   - `str::encode();`
   - `str::decode();`
- Updated sanitize function to move acceptable HTML strings into global config value.
- Add `timedate::` class, with `format()` and `valid()` method.
- Add `password::` class with `encrypt()` and `memorable()` methods.
- Update `str::titlecase()`, was running duplicate against camelcase.
- Added `str::numbers($str);` to convert numbers to number words.


##Release 1.0 July 2012

Initial release after converting several versions of functions files into class method calls.
