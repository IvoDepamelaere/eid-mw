ACLOCAL_AMFLAGS = -I scripts/m4
EXTRA_DIST = scripts/build-aux/config.rpath scripts/build-aux/genver.sh .version debian rpm doc

SUBDIRS=cardcomm/pkcs11/src doc/sdk/include/rsaref220 plugins_tools/util tests/unit plugins_tools/xpi

if GTK
SUBDIRS += plugins_tools/aboutmw/gtk plugins_tools/eid-viewer
endif

xpipackage:
	$(MAKE) -C plugins_tools/xpi xpipackage
