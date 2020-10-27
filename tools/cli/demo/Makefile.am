noinst_LTLIBRARIES = libdemocli.la

libdemocli_la_CPPFLAGS = -I$(top_srcdir)/include \
			 -I$(top_srcdir)/idl \
			 -I$(top_builddir)/idl \
			 -I/opt/likewise/include 
libdemocli_la_SOURCES = \
    demo_help.c \
    demo_main.c \
    demo_parseargs.c

libdemocli_la_LDFLAGS =  \
    -static
