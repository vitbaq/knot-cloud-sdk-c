lib_headers =
lib_sources =

libknotcloudsdkc_includedir = $(includedir)/knot
libknotcloudsdkc_include_HEADERS = $(lib_headers)

lib_LTLIBRARIES = libknotcloudsdkc.la
libknotcloudsdkc_la_SOURCES = $(lib_headers) $(lib_sources)
libknotcloudsdkc_la_LDFLAGS = $(AM_LDFLAGS)

pkgconfigdir = $(libdir)/pkgconfig

pkgconfig_DATA = knotcloudsdkc.pc
