MCS_BUILD_DIR = ../../../build

thisdir = class/Facades/System.Xml.XDocument
SUBDIRS = 
include $(MCS_BUILD_DIR)/rules.make

LIBRARY_SUBDIR = Facades
LIBRARY_INSTALL_DIR = $(mono_libdir)/mono/$(FRAMEWORK_VERSION)/Facades

LIBRARY = System.Xml.XDocument.dll

KEY_FILE = ../../msfinal.pub
SIGN_FLAGS = /delaysign /keyfile:$(KEY_FILE) /nowarn:1616,1699
LIB_REFS = System.Xml.Linq System.Xml
LIB_MCS_FLAGS = $(SIGN_FLAGS) /r:mscorlib.dll

PLATFORM_DEBUG_FLAGS =

NO_TEST = yes

include $(MCS_BUILD_DIR)/library.make


