# Makefile.am for hello/src.
#
# Copyright 1996, 1997, 2001, 2005, 2006, 2007, 2008 Free Software
# Foundation, Inc.
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

bin_PROGRAMS = hello
hello_SOURCES = hello.c system.h

hello_LDADD = $(LIBINTL) $(top_builddir)/lib/lib$(PACKAGE).a

localedir = $(datadir)/locale

AM_CPPFLAGS = -I$(top_srcdir)/lib -I$(top_builddir)/lib
DEFS = -DLOCALEDIR=\"$(localedir)\" @DEFS@
