ACLOCAL_AMFLAGS = -I m4
bin_PROGRAMS = hello bonjour
hello_SOURCES = src/hello.c src/say.c src/common.h
hello_CPPFLAGS = -I$(top_srcdir)/include
hello_LDADD = libdemo.la
bonjour_SOURCES = src/bonjour.c src/say.c src/common.h
if DEBUG_ENABLED
lib_LTLIBRARIES = libdemo.la
libdemo_la_SOURCES = lib/debug.c
libdemo_la_LDFLAGS = -version-info 0:0:0
endif
doc_DATA = README
