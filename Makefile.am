AUTOMAKE_OPTIONS = subdir-objects
lib_LTLIBRARIES = liblz4-@LZ4_API_VERSION@.la
liblz4_@LZ4_API_VERSION@_la_SOURCES = src/lz4.c
liblz4_@LZ4_API_VERSION@_la_LDFLAGS = -version-info $(LZ4_SO_VERSION)
liblz4_@LZ4_API_VERSION@_la_CFLAGS = -O3 -std=c99 -Wall -W -Wundef -Wno-implicit-function-declaration

liblz4_includedir = $(includedir)/lz4-$(LZ4_API_VERSION)
liblz4_include_HEADERS = src/lz4.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = lz4-$(LZ4_API_VERSION).pc
