ACLOCAL_AMFLAGS = -I m4

SUBDIRS = include

AM_CFLAGS = \
	-std=c99 \
	-pedantic \
	-Wall \
	-Wextra \
	-I$(top_builddir)/include \
	-I$(top_srcdir)/include

bin_PROGRAMS = autotools-project
lib_LTLIBRARIES = libautotools-project.la

autotools_project_SOURCES = \
	src/main.c

libautotools_project_la_SOURCES = \
	src/lib.c
