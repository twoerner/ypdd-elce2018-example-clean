## Copyright (C) 2018  Trevor Woerner <Trevor Woerner <twoerner@gmail.com>>

########################
## lib/Makefile.am
########################
SUBDIRS =

AM_CFLAGS = -Wall -Werror -Wextra
pkginclude_HEADERS = libypdd-elce2018-example.h

########################
## shared lib
########################
lib_LTLIBRARIES = libypdd-elce2018-example.la
libypdd_elce2018_example_la_SOURCES = libypdd-elce2018-example.c libypdd-elce2018-example.h
libypdd_elce2018_example_la_LDFLAGS =  -release @VERSION@
libypdd_elce2018_example_la_LDFLAGS += -version-info 1:0:0
