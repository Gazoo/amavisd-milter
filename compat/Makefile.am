# Distribution files
EXTRA_DIST= \
	.editorconfig \
	Makefile.am \
	Makefile.in

# Header files
noinst_HEADERS=	\
	compat.h \
	fts_compat.h

# Libraries
noinst_LIBRARIES= \
	libcompat.a

# libcompat compiling parameters
libcompat_a_SOURCES= \
	read_sock.c \
	write_sock.c
libcompat_a_LIBADD= \
	@LIBOBJS@
libcompat_a_DEPENDENCIES= \
	@LIBOBJS@

maintainer-clean-local:
	-rm -f Makefile.in
