thisdir = nunit24/NUnitExtensions/framework
SUBDIRS = 
include ../../../build/rules.make

LIBRARY = nunit.framework.extensions.dll
KEYFILE = $(topdir)/nunit24/nunit.pub

LIB_MCS_FLAGS = /d:StronglyNamedAssembly /delaysign
LIB_REFS = System.Xml System
NO_TEST = yo

EXTRA_DISTFILES = \
	nunit.framework.extensions.dll.csproj \
	nunit.framework.extensions.dll_VS2005.csproj

include ../../../build/library.make
