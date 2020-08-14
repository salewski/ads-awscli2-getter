# ads-awscli2-getter

## Retrieves the latest awscli2 installer


# Overview

This is just a scrappy little script to document and automate the process of
retrieving the `awscli2` installer from the Amazon AWS site:

   * https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip

The tool knows where to retrieve the latest awscli2 installer (see above link)
downloads it, and then prints a hint about what to do next.

Note that the hint reflects the author's personal setup, tailored for the way
he does things. It is geared toward the long-term maintainability of the
system rather than getting the tool installed as quickly as possible.


# Q: Do I need this tool?

**A:** Almost certainly not. The `awscli2` installer comes with instructions
that will probably work well enough for most folks; no need to complicate
things by deviating from those instructions.


# License

GPLv2+: GNU GPL version 2 or later <http://gnu.org/licenses/gpl.html>

Unless otherwise stated by a different license notice in a particular file,
all files in the `ads-awscli2-getter' project are made available under the GNU
GPL version 2, or (at your option) any later version.

See the [COPYING] file for the full license.

Copyright (C) 2020 Alan D. Salewski <salewski@att.net>

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.


[COPYING]:      https://github.com/salewski/ads-awscli2-getter/blob/master/COPYING
