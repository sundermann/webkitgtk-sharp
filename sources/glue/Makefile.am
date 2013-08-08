lib_LTLIBRARIES = libwebkitgtksharpglue-1.10.2.la

libwebkitgtksharpglue_1_10_2_la_SOURCES =

nodist_libwebkitgtksharpglue_1_10_2_la_SOURCES = generated.c

libwebkitgtksharpglue_1_10_2_la_LDFLAGS = -module -avoid-version -no-undefined

libwebkitgtksharpglue_1_10_2_la_LIBADD = $(WEBKIT_LIBS)

INCLUDES = $(WEBKIT_CFLAGS) -I$(top_srcdir)

libwebkitgtksharpglue.dll: $(libwebkitgtksharpglue_1_10_2_la_OBJECTS) libwebkitgtksharpglue.rc libwebkitgtksharpglue.def
	./build-dll libwebkitgtksharpglue $(VERSION)

CLEANFILES = lib*.a lib*.dll

EXTRA_DIST =
