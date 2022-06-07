SUBDIRS = include

AM_CFLAGS = \
	-std=c99 \
	-pedantic \
	-Wall \
	-Wextra \
	-I$(top_builddir)/include \
	-I$(top_srcdir)/include

bin_PROGRAMS = autotools-project
lib_LIBRARIES = libautotools-project.a

autotools_project_SOURCES = \
	src/main.c

libautotools_project_a_SOURCES = \
	src/lib.c
