################################################################################
#  THIS FILE IS 100% GENERATED BY ZPROJECT; DO NOT EDIT EXCEPT EXPERIMENTALLY  #
#  Read the zproject/README.md for information about making permanent changes. #
################################################################################

DISTCHECK_CONFIGURE_FLAGS = \
  --with-systemdsystemunitdir=$$dc_install_base/$(systemdsystemunitdir)

ACLOCAL_AMFLAGS = -I config

AM_CFLAGS = \
    -Werror=format-security


AM_CPPFLAGS = \
    ${libzmq_CFLAGS} \
    ${czmq_CFLAGS} \
    ${malamute_CFLAGS} \
    ${fty_proto_CFLAGS} \
    -I$(srcdir)/include

project_libs = ${libzmq_LIBS} ${czmq_LIBS} ${malamute_LIBS} ${fty_proto_LIBS}

SUBDIRS = doc
DIST_SUBDIRS = doc
lib_LTLIBRARIES =
bin_PROGRAMS =
noinst_PROGRAMS =
check_PROGRAMS =
noinst_LTLIBRARIES =
TESTS =
# Prepare variables that can be populated (appended) in generated Makefiles or
# manually maintained src/Makemodules-local.am
EXTRA_DIST =
CLEANFILES =
DISTCLEANFILES =

if ENABLE_DIST_CMAKEFILES
EXTRA_DIST += \
    Findlibzmq.cmake \
    Findczmq.cmake \
    Findmalamute.cmake \
    Findfty_proto.cmake \
    CMakeLists.txt
endif

EXTRA_DIST += \
    LICENSE \
    README.md \
    src/fty_example_classes.h

include $(srcdir)/src/Makemodule.am

################################################################################
#  THIS FILE IS 100% GENERATED BY ZPROJECT; DO NOT EDIT EXCEPT EXPERIMENTALLY  #
#  Read the zproject/README.md for information about making permanent changes. #
################################################################################
