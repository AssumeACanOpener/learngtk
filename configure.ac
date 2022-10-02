AC_PREREQ([2.71])
AC_INIT([learngtk], [0.1], [gkaukola@cs.ucr.edu])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([1.16.5 -Wall -Werror dist-bzip2])
AC_CONFIG_SRCDIR([src/learngtk.c])
AC_CONFIG_HEADERS([config.h])
AC_PROG_CC
AC_PROG_INSTALL
PKG_CHECK_MODULES([GTK], [gtk+-3.0])
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
