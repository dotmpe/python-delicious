0.5.1
    Lots of cosmetic changes in formatting, documentation.
    Slight update to some methods for hashes/meta params.
    Now raising errors on API failures. API acts silently (when successful).
    Removed post and posts class (will only get back, as needed, in a slightly better form).
    tools/dlcs is not tested and not included in zipped package.
    Feedparser is now optional.

0.5.2-rc1
    Now raises Exceptions for API errors. Methods do no longer return {'result:..}
    data. May break existing code.
    Added preliminary support for v1 feeds but not sure yet on dependencies
    (keep using feedparser from pydelicious.py? add (simple)json?)
    HTTP request now works on urllib2 opener that needs only be created once, instead of
    every request. This opener now also handles 503 (throttled) and 401 (unauthorized).
    Numerous cosmetic, formatting changes, slight fixes, etc.

0.5.2-rc2
    raiseFor code fixed (thnx to me.gooz), added test
    getpreferredencoding on Mac OS X 10.5 returning empty defaults to iso8859-1 (thnx to mohangk)
    added first HTTP proxy support (suggestion by aman.coe)
    fixed issue 28, thanks ZebraShaSha
    worked around stdlib deprecation warning (Py2.6), fixed issue 27 (thanks, stumble.then.rise)

0.5.3
    make install now installs tools also

0.6
  HTTP(S)_PROXY for https too
  merge setup_tools into setup, dlcs for command line del.icio.us now available

0.6.1
  - Changed back to semver compatible version.
  - Installable package for the Google Code SVN export (master), registered with
    PyPi.

(0.6.2)
  ..

