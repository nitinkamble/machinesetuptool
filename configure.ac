AC_PREREQ(2.53)
AC_INIT(machinesetuptool, 0.1.0, http://www.yoctoproject.org/)
AM_INIT_AUTOMAKE()

AC_ISC_POSIX
AC_PROG_INSTALL

appconfdir="$sysconfdir/$PACKAGE"

AC_SUBST(sysconfdir)
AC_SUBST(appconfdir)
AC_SUBST(base_sbindir)

AC_CONFIG_FILES([
  Makefile
  setup
  config/Makefile
  scripts/Makefile
  scripts/machinesetuptool
  scripts/machine-selection-menu
])

AC_OUTPUT
