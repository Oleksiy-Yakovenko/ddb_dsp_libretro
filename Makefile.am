if HAVE_LIBRETRO
pkglib_LTLIBRARIES = ddb_dsp_libretro.la
ddb_dsp_libretro_la_SOURCES = libretro.cpp
ddb_dsp_libretro_la_LDFLAGS = -module -avoid-version
ddb_dsp_libretro_la_CXXFLAGS = $(CFLAGS) -msse3 -std=c++11
endif
