noinst_LTLIBRARIES = librolemgmtcli.la

librolemgmtcli_la_CPPFLAGS = \
    -I$(top_srcdir)/include \
    -I$(top_srcdir)/idl \
    -I$(top_builddir)/idl \
    -I/opt/likewise/include 

librolemgmtcli_la_SOURCES = \
    rolemgmt_help.c \
    rolemgmt_main.c \
    rolemgmt_parseargs.c

librolemgmtcli_la_LDFLAGS =  \
    -static
