# NAME

difflists - show differences between two lists

# SYNOPSIS

difflists \[--unique\] \[--bare\] \[--same|--diff|--left\] `file_a` `file_b`

difflists \[-u\] \[-b\] \[-s|-d|-l\] `file_a` `file_b`

difflists --help    # for full documentation

# DESCRIPTION

Show differences between two lists in a format like 'diff -y', but
where every difference creates is a new line instead of attempting to
find changes within a line. difflists sorts the incoming lists.

- -b, --bare

    don't show >< symbols

- -d, --diff

    show only entries missing from either list (only how they differ)

- -l, --left

    like --diff, but only show entries from the left file

- -s, --same

    show only entries that only occur in both lists (only how they are the same)

- -u, --unique

    exclude duplicates from the output

The use of --diff, --left and --same are mutually exclusive.

# AUTHOR

Carl Cravens - [http://github.com/ravenx99](http://github.com/ravenx99)

# AVAILABILITY

[http://github.com/ravenx99/difflists](http://github.com/ravenx99/difflists)

# LICENSE

**Copyright 2016 Carl D Cravens**

This program comes with NO WARRANTY, to the extent permitted by law.
You may redistribute copies of this program under the terms of the GNU
General Public License.  For more information about these matters, see
the file named COPYING.

# SEE ALSO

diff
