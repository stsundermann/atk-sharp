lib_LTLIBRARIES = libatksharpglue-2.8.0.la

libatksharpglue_2_8_0_la_SOURCES =

nodist_libatksharpglue_2_8_0_la_SOURCES = generated.c

libatksharpglue_2_8_0_la_LDFLAGS = -module -avoid-version -no-undefined

libatksharpglue_2_8_0_la_LIBADD = $(ATK_LIBS)

INCLUDES = $(ATK_CFLAGS) -I$(top_srcdir)

libatksharpglue.dll: $(libatksharpglue_2_8_0_la_OBJECTS) libatksharpglue.rc libatksharpglue.def
	./build-dll libatksharpglue $(VERSION)

CLEANFILES = lib*.a lib*.dll

EXTRA_DIST =
