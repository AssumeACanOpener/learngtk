AC_PREREQ([2.68])
AC_INIT([learngtk], [0.1], [gkaukola@cs.ucr.edu])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([1.11.3 -Wall -Werror dist-bzip2])
AC_CONFIG_SRCDIR([src/learngtk.c])
AC_CONFIG_HEADERS([config.h])
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_LIBTOOL
AM_PATH_GTK_2_0([2.24.11],,AC_MSG_ERROR([Gtk+ 2.24.11 or higher required.]))
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
