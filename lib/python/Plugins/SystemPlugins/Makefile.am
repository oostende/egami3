installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = PositionerSetup Satfinder Toolkit \
	VideoTune Hotplug SoftwareManager \
	VideoClippingSetup CommonInterfaceAssignment \
	HdmiCEC WirelessLan NetworkWizard NetworkBrowser \
	Satfinder DiseqcTester SatelliteEquipmentControl

if VUSOLO2
SUBDIRS += CableScan
endif

if VUSOLOSE
SUBDIRS += CableScan
endif

if VUDUO2
SUBDIRS += CableScan
endif

if VUUNO
SUBDIRS += CableScan
endif

if VUULTIMO
SUBDIRS += CableScan
endif

if VUSOLO4K
SUBDIRS += CableScan
endif

if VUUNO4K
SUBDIRS += CableScan
endif

if VUULTIMO4K
SUBDIRS += CableScan
endif

if HAVE_LIBVUGLES2
SUBDIRS += AnimationSetup
endif

if HAVE_OSDANIMATION
SUBDIRS += AnimationSetup
endif

install_PYTHON = __init__.py
