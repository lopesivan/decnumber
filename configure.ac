AC_INIT([libdecnumber], [368], [omari@smileystation.com])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([-Wall foreign])
LT_INIT
AC_PROG_CC
AC_C_BIGENDIAN( [AC_DEFINE([DECLITEND], [0])], [AC_DEFINE([DECLITEND], [1])]
                , AC_MSG_ERROR([Cannot determine endianness])
                , AC_MSG_ERROR([Cannot determine endianness]) )
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
