dnl Process this file with autoconf to produce a configure script.

AC_INIT([robodoc], [3.2.4])
AC_CONFIG_SRCDIR([Source/robodoc.h])
AC_CONFIG_HEADERS([Source/config.h])

AM_INIT_AUTOMAKE
AM_MAINTAINER_MODE([disable])

AC_PROG_MAKE_SET

dnl Checks for programs.
AC_PROG_CC

dnl Checks for libraries.

dnl Checks for header files.
AC_CHECK_INCLUDES_DEFAULT
AC_PROG_EGREP

dnl Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST
AC_TYPE_SIZE_T

dnl Checks for library functions.
AC_FUNC_STRFTIME
AC_FUNC_VPRINTF
AC_CHECK_FUNCS(strstr)

AC_CONFIG_FILES([makefile Docs/makefile Source/makefile])
AC_OUTPUT

