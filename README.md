difflists
=========

**difflists** - show differences between two lists


DESCRIPTION
-----------

Show differences between two lists in a format like 'diff -y', but
where every difference is a new line instead of thinking a line has
changed in place.  difflists sorts the incoming lists.


DEPENDENCIES
------------

Requires Perl >5.010.


USAGE
-----

difflists [--unique] [--both|--diff] <file_a> <file_b>

Flags can be shortened to a single character and can be grouped,
e.g. -ud.

--unique  filter our duplicate entries within each file individually

--both    show only entries that occur in both lists

--diff    show only entries that occur in one list

Use of --both and --diff are mutually exclusive.


AUTHOR
------

  Carl D Cravens <raven@phoenyx.net>


LICENSE & COPYRIGHT
-------------------

**Copyright 2016 Carl D Cravens**

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

------------------------------------------------------------------------

VERSION: 0.0.4

Source repo: <https://github.com/ravenx99/difflists/>

------------------------------------------------------------------------
