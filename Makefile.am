ACLOCAL_AMFLAGS = -I m4
bin_PROGRAMS = Code2

Code2_SOURCES = src/Code2.c src/pole.h src/objetosc.h
Code2_DEPENDENCIES = libpole.a libobj.la
  
noinst_LIBRARIES = libpole.a 
lib_LTLIBRARIES = libobj.la

libpole_a_SOURCES = src/pole.c
libobj_la_SOURCES = src/objetosc.c

#libpole_a_LDFLAGS = -version-info 1:0:0
libobj_la_LDFLAGS = -version-info 1:0:0

Code2_LDADD = libpole.a libobj.la
Code2_LDFLAGS= -rpath /usr/local/lib
