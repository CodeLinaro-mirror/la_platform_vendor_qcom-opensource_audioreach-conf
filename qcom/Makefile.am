kvh2xml_headers = kvh2xml.h

kvh2xml_includedir = $(includedir)
kvh2xml_include_HEADERS = $(kvh2xml_headers)

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = kvh2xml.pc
EXTRA_DIST = $(pkgconfig_DATA)

if BUILDSYSTEM_OPENWRT
SUBDIRS = mbb/sdx_target
else
SUBDIRS = qli/qcm6490 qli/qcs8300 qli/qcs9100 qli/qcs9075
endif
