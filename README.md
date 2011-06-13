lolcode-mode
============

A major mode for editing LOLCODE.

Copyright (C) 2011 Bodil Stokke

License
-------

This file is not part of GNU Emacs.

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2, or (at your option)
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.

Commentary
----------

This is a major mode for editing LOLCODE, with the following
features:

* Syntax highlighting.
* Smart indentation.
* Execution of LOLCODE buffers (press `C-c C-C`).

Installation
------------

Put this file somewhere in your load-path, and put the following in
your .emacs:

    (require 'lolcode-mode)

You may want to install a LOLCODE interpreter. This package comes
preconfigured for lci, which you can get from <http://icanhaslolcode.org/>.
  

