AC_PREREQ([2.63])
AC_INIT([eos-base-files], [1.0.0], [cosimo@endlessm.com], [base-files], [http://www.endlessm.com/])
AC_CONFIG_HEADER([config.h])
AC_CONFIG_MACRO_DIR([m4])

m4_define(endless_platform, 2)
m4_define(endless_minor, 6)
m4_define(endless_micro, 3)

ENDLESS_PLATFORM=endless_platform
ENDLESS_MINOR=endless_minor
ENDLESS_MICRO=endless_micro

OS_NAME="Endless"
OS_ID="endless"
OS_VERSION="$ENDLESS_PLATFORM.$ENDLESS_MINOR.$ENDLESS_MICRO"
OS_PRETTY_NAME="$OS_NAME $OS_VERSION"

AC_SUBST([OS_NAME])
AC_SUBST([OS_ID])
AC_SUBST([OS_VERSION])
AC_SUBST([OS_PRETTY_NAME])

AM_INIT_AUTOMAKE([1.11 -Wno-portability foreign no-define tar-ustar no-dist-gzip dist-xz])
AM_MAINTAINER_MODE([enable])
AM_SILENT_RULES([yes])

AC_CONFIG_FILES([
Makefile
])
AC_OUTPUT

echo "
    Endless base files $VERSION
"
