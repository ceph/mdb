AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = -I m4
CC      = gcc
W       = -W -Wall -Wno-unused-parameter -Wbad-function-cast -Wuninitialized
OPT = -O2 -g 

LIBS = 

bin_PROGRAMS = 

noinst_LTLIBRARIES = liblmdb.la

AM_CFLAGS  = $(OPT) $(W) $(XCFLAGS) -fPIC
SOURCE_FILE = mdb.c midl.c lmdb.h midl.h

liblmdb_la_SOURCES = $(SOURCE_FILE)

