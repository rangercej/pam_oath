## DO NOT EDIT! GENERATED AUTOMATICALLY!
## Process this file with automake to produce Makefile.in.
# Copyright (C) 2002-2016 Free Software Foundation, Inc.
#
# This file is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3 of the License, or
# (at your option) any later version.
#
# This file is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this file.  If not, see <http://www.gnu.org/licenses/>.
#
# As a special exception to the GNU General Public License,
# this file may be distributed as part of a program that
# contains a configuration script generated by Autoconf, under
# the same distribution terms as the rest of that program.
#
# Generated by gnulib-tool.

AUTOMAKE_OPTIONS = 1.9.6 foreign

SUBDIRS = .
TESTS =
XFAIL_TESTS =
TESTS_ENVIRONMENT =
noinst_PROGRAMS =
check_PROGRAMS =
noinst_HEADERS =
noinst_LIBRARIES =
check_LIBRARIES = libtests.a
EXTRA_DIST =
BUILT_SOURCES =
SUFFIXES =
MOSTLYCLEANFILES = core *.stackdump
MOSTLYCLEANDIRS =
CLEANFILES =
DISTCLEANFILES =
MAINTAINERCLEANFILES =

AM_CPPFLAGS = \
  -D@gltests_WITNESS@=1 \
  -I. -I$(srcdir) \
  -I../.. -I$(srcdir)/../.. \
  -I../../gl -I$(srcdir)/../../gl

LDADD = libtests.a ../../gl/libgnu.la libtests.a $(LIBTESTS_LIBDEPS)

libtests_a_SOURCES =
libtests_a_LIBADD = $(gltests_LIBOBJS)
libtests_a_DEPENDENCIES = $(gltests_LIBOBJS)
EXTRA_libtests_a_SOURCES =
AM_LIBTOOLFLAGS = --preserve-dup-deps

TESTS_ENVIRONMENT += EXEEXT='@EXEEXT@' srcdir='$(srcdir)'

## begin gnulib module alloca-opt-tests

TESTS += test-alloca-opt
check_PROGRAMS += test-alloca-opt

EXTRA_DIST += test-alloca-opt.c

## end   gnulib module alloca-opt-tests

## begin gnulib module c-ctype-tests

TESTS += test-c-ctype
check_PROGRAMS += test-c-ctype
EXTRA_DIST += test-c-ctype.c macros.h

## end   gnulib module c-ctype-tests

## begin gnulib module ctype

BUILT_SOURCES += ctype.h

# We need the following in order to create <ctype.h> when the system
# doesn't have one that works with the given compiler.
ctype.h: ctype.in.h $(top_builddir)/config.status $(CXXDEFS_H) $(WARN_ON_USE_H)
	$(AM_V_GEN)rm -f $@-t $@ && \
	{ echo '/* DO NOT EDIT! GENERATED AUTOMATICALLY! */'; \
	  sed -e 's|@''GUARD_PREFIX''@|GL|g' \
	      -e 's|@''INCLUDE_NEXT''@|$(INCLUDE_NEXT)|g' \
	      -e 's|@''PRAGMA_SYSTEM_HEADER''@|@PRAGMA_SYSTEM_HEADER@|g' \
	      -e 's|@''PRAGMA_COLUMNS''@|@PRAGMA_COLUMNS@|g' \
	      -e 's|@''NEXT_CTYPE_H''@|$(NEXT_CTYPE_H)|g' \
	      -e 's/@''GNULIB_ISBLANK''@/$(GNULIB_ISBLANK)/g' \
	      -e 's/@''HAVE_ISBLANK''@/$(HAVE_ISBLANK)/g' \
	      -e '/definitions of _GL_FUNCDECL_RPL/r $(CXXDEFS_H)' \
	      -e '/definition of _GL_WARN_ON_USE/r $(WARN_ON_USE_H)' \
	      < $(srcdir)/ctype.in.h; \
	} > $@-t && \
	mv $@-t $@
MOSTLYCLEANFILES += ctype.h ctype.h-t

EXTRA_DIST += ctype.in.h

## end   gnulib module ctype

## begin gnulib module ctype-tests

TESTS += test-ctype
check_PROGRAMS += test-ctype
EXTRA_DIST += test-ctype.c

## end   gnulib module ctype-tests

## begin gnulib module dtotimespec

libtests_a_SOURCES += dtotimespec.c

## end   gnulib module dtotimespec

## begin gnulib module environ-tests

TESTS += test-environ
check_PROGRAMS += test-environ

EXTRA_DIST += test-environ.c

## end   gnulib module environ-tests

## begin gnulib module errno-tests

TESTS += test-errno
check_PROGRAMS += test-errno

EXTRA_DIST += test-errno.c

## end   gnulib module errno-tests

## begin gnulib module fdopen


EXTRA_DIST += fdopen.c

EXTRA_libtests_a_SOURCES += fdopen.c

## end   gnulib module fdopen

## begin gnulib module fdopen-tests

TESTS += test-fdopen
check_PROGRAMS += test-fdopen
EXTRA_DIST += test-fdopen.c signature.h macros.h

## end   gnulib module fdopen-tests

## begin gnulib module fgetc-tests

TESTS += test-fgetc
check_PROGRAMS += test-fgetc
EXTRA_DIST += test-fgetc.c signature.h macros.h

## end   gnulib module fgetc-tests

## begin gnulib module float-tests

TESTS += test-float
check_PROGRAMS += test-float
EXTRA_DIST += test-float.c macros.h

## end   gnulib module float-tests

## begin gnulib module fpucw


EXTRA_DIST += fpucw.h

## end   gnulib module fpucw

## begin gnulib module fputc-tests

TESTS += test-fputc
check_PROGRAMS += test-fputc
EXTRA_DIST += test-fputc.c signature.h macros.h

## end   gnulib module fputc-tests

## begin gnulib module fread-tests

TESTS += test-fread
check_PROGRAMS += test-fread
EXTRA_DIST += test-fread.c signature.h macros.h

## end   gnulib module fread-tests

## begin gnulib module fwrite-tests

TESTS += test-fwrite
check_PROGRAMS += test-fwrite
EXTRA_DIST += test-fwrite.c signature.h macros.h

## end   gnulib module fwrite-tests

## begin gnulib module getpagesize


EXTRA_DIST += getpagesize.c

EXTRA_libtests_a_SOURCES += getpagesize.c

## end   gnulib module getpagesize

## begin gnulib module getprogname-tests

DEFS += -DEXEEXT=\"@EXEEXT@\"
TESTS += test-getprogname
check_PROGRAMS += test-getprogname
test_getprogname_LDADD = $(LDADD)
EXTRA_DIST += test-getprogname.c

## end   gnulib module getprogname-tests

## begin gnulib module gettimeofday-tests

TESTS += test-gettimeofday
check_PROGRAMS += test-gettimeofday

EXTRA_DIST += signature.h test-gettimeofday.c

## end   gnulib module gettimeofday-tests

## begin gnulib module intprops-tests

TESTS += test-intprops
check_PROGRAMS += test-intprops
EXTRA_DIST += test-intprops.c macros.h

## end   gnulib module intprops-tests

## begin gnulib module inttypes-tests

TESTS += test-inttypes
check_PROGRAMS += test-inttypes
EXTRA_DIST += test-inttypes.c

## end   gnulib module inttypes-tests

## begin gnulib module limits-h-tests

TESTS += test-limits-h
check_PROGRAMS += test-limits-h
EXTRA_DIST += test-limits-h.c

## end   gnulib module limits-h-tests

## begin gnulib module malloca-tests

TESTS += test-malloca
check_PROGRAMS += test-malloca

EXTRA_DIST += test-malloca.c

## end   gnulib module malloca-tests

## begin gnulib module memchr-tests

TESTS += test-memchr
check_PROGRAMS += test-memchr
EXTRA_DIST += test-memchr.c zerosize-ptr.h signature.h macros.h

## end   gnulib module memchr-tests

## begin gnulib module parse-datetime-tests

TESTS += test-parse-datetime
check_PROGRAMS += test-parse-datetime
test_parse_datetime_LDADD = $(LDADD) @LIBINTL@ $(LIB_CLOCK_GETTIME)
EXTRA_DIST += test-parse-datetime.c macros.h

## end   gnulib module parse-datetime-tests

## begin gnulib module parse-duration-tests

TESTS += test-parse-duration.sh
check_PROGRAMS += test-parse-duration
test_parse_duration_LDADD = $(LDADD)
EXTRA_DIST += test-parse-duration.sh test-parse-duration.c

## end   gnulib module parse-duration-tests

## begin gnulib module putenv


EXTRA_DIST += putenv.c

EXTRA_libtests_a_SOURCES += putenv.c

## end   gnulib module putenv

## begin gnulib module setenv-tests

TESTS += test-setenv
check_PROGRAMS += test-setenv
EXTRA_DIST += test-setenv.c signature.h macros.h

## end   gnulib module setenv-tests

## begin gnulib module snippet/_Noreturn

# Because this Makefile snippet defines a variable used by other
# gnulib Makefile snippets, it must be present in all Makefile.am that
# need it. This is ensured by the applicability 'all' defined above.

_NORETURN_H=$(top_srcdir)/build-aux/snippet/_Noreturn.h

EXTRA_DIST += $(top_srcdir)/build-aux/snippet/_Noreturn.h

## end   gnulib module snippet/_Noreturn

## begin gnulib module snippet/arg-nonnull

# The BUILT_SOURCES created by this Makefile snippet are not used via #include
# statements but through direct file reference. Therefore this snippet must be
# present in all Makefile.am that need it. This is ensured by the applicability
# 'all' defined above.

BUILT_SOURCES += arg-nonnull.h
# The arg-nonnull.h that gets inserted into generated .h files is the same as
# build-aux/snippet/arg-nonnull.h, except that it has the copyright header cut
# off.
arg-nonnull.h: $(top_srcdir)/build-aux/snippet/arg-nonnull.h
	$(AM_V_GEN)rm -f $@-t $@ && \
	sed -n -e '/GL_ARG_NONNULL/,$$p' \
	  < $(top_srcdir)/build-aux/snippet/arg-nonnull.h \
	  > $@-t && \
	mv $@-t $@
MOSTLYCLEANFILES += arg-nonnull.h arg-nonnull.h-t

ARG_NONNULL_H=arg-nonnull.h

EXTRA_DIST += $(top_srcdir)/build-aux/snippet/arg-nonnull.h

## end   gnulib module snippet/arg-nonnull

## begin gnulib module snippet/c++defs

# The BUILT_SOURCES created by this Makefile snippet are not used via #include
# statements but through direct file reference. Therefore this snippet must be
# present in all Makefile.am that need it. This is ensured by the applicability
# 'all' defined above.

BUILT_SOURCES += c++defs.h
# The c++defs.h that gets inserted into generated .h files is the same as
# build-aux/snippet/c++defs.h, except that it has the copyright header cut off.
c++defs.h: $(top_srcdir)/build-aux/snippet/c++defs.h
	$(AM_V_GEN)rm -f $@-t $@ && \
	sed -n -e '/_GL_CXXDEFS/,$$p' \
	  < $(top_srcdir)/build-aux/snippet/c++defs.h \
	  > $@-t && \
	mv $@-t $@
MOSTLYCLEANFILES += c++defs.h c++defs.h-t

CXXDEFS_H=c++defs.h

EXTRA_DIST += $(top_srcdir)/build-aux/snippet/c++defs.h

## end   gnulib module snippet/c++defs

## begin gnulib module snippet/warn-on-use

BUILT_SOURCES += warn-on-use.h
# The warn-on-use.h that gets inserted into generated .h files is the same as
# build-aux/snippet/warn-on-use.h, except that it has the copyright header cut
# off.
warn-on-use.h: $(top_srcdir)/build-aux/snippet/warn-on-use.h
	$(AM_V_GEN)rm -f $@-t $@ && \
	sed -n -e '/^.ifndef/,$$p' \
	  < $(top_srcdir)/build-aux/snippet/warn-on-use.h \
	  > $@-t && \
	mv $@-t $@
MOSTLYCLEANFILES += warn-on-use.h warn-on-use.h-t

WARN_ON_USE_H=warn-on-use.h

EXTRA_DIST += $(top_srcdir)/build-aux/snippet/warn-on-use.h

## end   gnulib module snippet/warn-on-use

## begin gnulib module stdalign

BUILT_SOURCES += $(STDALIGN_H)

# We need the following in order to create <stdalign.h> when the system
# doesn't have one that works.
if GL_GENERATE_STDALIGN_H
stdalign.h: stdalign.in.h $(top_builddir)/config.status
	$(AM_V_GEN)rm -f $@-t $@ && \
	{ echo '/* DO NOT EDIT! GENERATED AUTOMATICALLY! */'; \
	  cat $(srcdir)/stdalign.in.h; \
	} > $@-t && \
	mv $@-t $@
else
stdalign.h: $(top_builddir)/config.status
	rm -f $@
endif
MOSTLYCLEANFILES += stdalign.h stdalign.h-t

EXTRA_DIST += stdalign.in.h

## end   gnulib module stdalign

## begin gnulib module stdalign-tests

TESTS += test-stdalign
check_PROGRAMS += test-stdalign
EXTRA_DIST += test-stdalign.c macros.h

## end   gnulib module stdalign-tests

## begin gnulib module stdbool-tests

TESTS += test-stdbool
check_PROGRAMS += test-stdbool
EXTRA_DIST += test-stdbool.c

## end   gnulib module stdbool-tests

## begin gnulib module stddef-tests

TESTS += test-stddef
check_PROGRAMS += test-stddef
EXTRA_DIST += test-stddef.c

## end   gnulib module stddef-tests

## begin gnulib module stdint-tests

TESTS += test-stdint
check_PROGRAMS += test-stdint
EXTRA_DIST += test-stdint.c

## end   gnulib module stdint-tests

## begin gnulib module stdio-tests

TESTS += test-stdio
check_PROGRAMS += test-stdio
EXTRA_DIST += test-stdio.c

## end   gnulib module stdio-tests

## begin gnulib module stdlib-tests

TESTS += test-stdlib
check_PROGRAMS += test-stdlib
EXTRA_DIST += test-stdlib.c test-sys_wait.h

## end   gnulib module stdlib-tests

## begin gnulib module strerror-tests

TESTS += test-strerror
check_PROGRAMS += test-strerror
EXTRA_DIST += test-strerror.c signature.h macros.h

## end   gnulib module strerror-tests

## begin gnulib module strftime-tests

TESTS += test-strftime
check_PROGRAMS += test-strftime
EXTRA_DIST += test-strftime.c macros.h

## end   gnulib module strftime-tests

## begin gnulib module string-tests

TESTS += test-string
check_PROGRAMS += test-string
EXTRA_DIST += test-string.c

## end   gnulib module string-tests

## begin gnulib module sys_time-tests

TESTS += test-sys_time
check_PROGRAMS += test-sys_time
EXTRA_DIST += test-sys_time.c

## end   gnulib module sys_time-tests

## begin gnulib module sys_types-tests

TESTS += test-sys_types
check_PROGRAMS += test-sys_types
EXTRA_DIST += test-sys_types.c

## end   gnulib module sys_types-tests

## begin gnulib module test-framework-sh-tests

TESTS += test-init.sh
EXTRA_DIST += init.sh
EXTRA_DIST += test-init.sh

## end   gnulib module test-framework-sh-tests

## begin gnulib module time-tests

TESTS += test-time
check_PROGRAMS += test-time
EXTRA_DIST += test-time.c

## end   gnulib module time-tests

## begin gnulib module timespec-add

libtests_a_SOURCES += timespec-add.c

## end   gnulib module timespec-add

## begin gnulib module timespec-sub

libtests_a_SOURCES += timespec-sub.c

## end   gnulib module timespec-sub

## begin gnulib module timespec-tests

TESTS += test-timespec
check_PROGRAMS += test-timespec
EXTRA_DIST += test-timespec.c macros.h

## end   gnulib module timespec-tests

## begin gnulib module unistd-tests

TESTS += test-unistd
check_PROGRAMS += test-unistd
EXTRA_DIST += test-unistd.c

## end   gnulib module unistd-tests

## begin gnulib module unsetenv-tests

TESTS += test-unsetenv
check_PROGRAMS += test-unsetenv
EXTRA_DIST += test-unsetenv.c signature.h macros.h

## end   gnulib module unsetenv-tests

## begin gnulib module vasnprintf-tests

TESTS += test-vasnprintf
check_PROGRAMS += test-vasnprintf

EXTRA_DIST += test-vasnprintf.c macros.h

## end   gnulib module vasnprintf-tests

## begin gnulib module vasprintf-tests

TESTS += test-vasprintf
check_PROGRAMS += test-vasprintf

EXTRA_DIST += test-vasprintf.c signature.h macros.h

## end   gnulib module vasprintf-tests

## begin gnulib module verify-tests

TESTS_ENVIRONMENT += MAKE='$(MAKE)'
TESTS += test-verify test-verify.sh
check_PROGRAMS += test-verify

# This test expects compilation of test-verify.c to fail, and
# each time it fails, the makefile rule does not perform the usual
#  "mv -f $name.Tpo $name.po, so tell make clean to remove that file.
MOSTLYCLEANFILES += .deps/test-verify.Tpo
EXTRA_DIST += test-verify.c test-verify.sh

## end   gnulib module verify-tests

## begin gnulib module version-etc-fsf

libtests_a_SOURCES += version-etc-fsf.c

## end   gnulib module version-etc-fsf

## begin gnulib module version-etc-tests

TESTS += test-version-etc.sh
check_PROGRAMS += test-version-etc
test_version_etc_LDADD = $(LDADD) @LIBINTL@
EXTRA_DIST += test-version-etc.c test-version-etc.sh

## end   gnulib module version-etc-tests

## begin gnulib module wchar-tests

TESTS += test-wchar
check_PROGRAMS += test-wchar
EXTRA_DIST += test-wchar.c

## end   gnulib module wchar-tests

## begin gnulib module xalloc-die-tests

TESTS += test-xalloc-die.sh
check_PROGRAMS += test-xalloc-die
test_xalloc_die_LDADD = $(LDADD) @LIBINTL@
EXTRA_DIST += test-xalloc-die.c test-xalloc-die.sh

## end   gnulib module xalloc-die-tests

# Clean up after Solaris cc.
clean-local:
	rm -rf SunWS_cache

mostlyclean-local: mostlyclean-generic
	@for dir in '' $(MOSTLYCLEANDIRS); do \
	  if test -n "$$dir" && test -d $$dir; then \
	    echo "rmdir $$dir"; rmdir $$dir; \
	  fi; \
	done; \
	:
