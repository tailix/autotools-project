############################
# Specify program versions #
############################

AC_PREREQ([2.70])
LT_PREREQ([2.4.6])



##################################
# Initialize Autoconf & Automake #
##################################

AC_INIT([autotools-project],
  m4_normalize(m4_include([VERSION])),
  [https://github.com/tailix/autotools-project/issues],
  [autotools-project],
  [https://github.com/tailix/autotools-project])

AC_CANONICAL_BUILD
AC_CANONICAL_HOST

AC_CONFIG_MACRO_DIRS([m4])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_SRCDIR([src/main.c])
AC_CONFIG_FILES([
  Makefile
  include/Makefile
])

AM_INIT_AUTOMAKE([1.16 subdir-objects])



##############
# Run checks #
##############

AC_LANG([C])

AM_PROG_AR
AM_PROG_AS
AC_PROG_CC
AC_C_INLINE
AC_CHECK_HEADER_STDBOOL
AC_CHECK_HEADERS([stdarg.h stddef.h stdint.h])



######################
# Initialize Libtool #
######################

LT_INIT([disable-shared])



##########
# Finish #
##########

AC_OUTPUT
