miscutil
========

miscellaneous utilities

bkp

  This is a script I wrote long ago.  The "-i" option for cp protects
  against a race condition that human users probably will never hit.
  A common pattern of mine is to use bash history like this,

    bkp ~/.hgrc
    vi !$

pppdfcode

  This script aids in reading source code "cover to cover" on an
  ereader.  That's something I need to do for work.

  Pretty print source code using enscript, and collect the generated
  PostScript into optionally encrypted PDF files.

  Tested on Mac OS X Snow Leopard with ghostscript from the Mac ports.

  See comments at the top for details.
