## Copyright (C) 2018  Trevor Woerner <Trevor Woerner <twoerner@gmail.com>>

########################
## src/Makefile.am
########################
SUBDIRS =
AM_CFLAGS = -Wall -Werror -Wextra -Wconversion -Wreturn-type -Wstrict-prototypes

bin_PROGRAMS = ypdd-elce2018-example
ypdd_elce2018_example_SOURCES = ypdd-elce2018-example.c
ypdd_elce2018_example_CFLAGS = -I$(top_srcdir)/lib
ypdd_elce2018_example_LDADD = $(top_builddir)/lib/libypdd-elce2018-example.la
