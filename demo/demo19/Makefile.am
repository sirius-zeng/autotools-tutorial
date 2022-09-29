bin_PROGRAMS = hello bonjour
hello_SOURCES = src/hello.c src/say.c src/common.h
bonjour_SOURCES = src/bonjour.c src/say.c src/common.h

hello_CPPFLAGS = -I$(top_srcdir)/include

if DEBUG_ENABLED
lib_LTLIBRARIES = libdemo.la
libdemo_la_SOURCES = lib/debug.c
libdemo_la_LDFLAGS = -version-info 0:0:0

hello_LDADD = libdemo.la
endif

doc_DATA = README
