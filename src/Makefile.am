bin_PROGRAMS = fileshelter

fileshelter_SOURCES = \
	$(srcdir)/main/main.cpp			\
	$(srcdir)/database/DbCleaner.cpp	\
	$(srcdir)/database/DbCleaner.hpp	\
	$(srcdir)/database/DbHandler.cpp	\
	$(srcdir)/database/DbHandler.hpp	\
	$(srcdir)/database/Share.cpp		\
	$(srcdir)/database/Share.hpp		\
	$(srcdir)/ui/FileShelterApplication.cpp	\
	$(srcdir)/ui/FileShelterApplication.hpp	\
	$(srcdir)/ui/ShareCommon.cpp		\
	$(srcdir)/ui/ShareCommon.hpp		\
	$(srcdir)/ui/ShareCreate.cpp		\
	$(srcdir)/ui/ShareCreate.hpp		\
	$(srcdir)/ui/ShareCreatePassword.cpp	\
	$(srcdir)/ui/ShareCreatePassword.hpp	\
	$(srcdir)/ui/ShareCreated.cpp		\
	$(srcdir)/ui/ShareCreated.hpp		\
	$(srcdir)/ui/ShareDownload.cpp		\
	$(srcdir)/ui/ShareDownload.hpp		\
	$(srcdir)/ui/ShareEdit.cpp		\
	$(srcdir)/ui/ShareEdit.hpp		\
	$(srcdir)/ui/ShareDownloadPassword.cpp	\
	$(srcdir)/ui/ShareDownloadPassword.hpp	\
	$(srcdir)/ui/ShareResource.cpp		\
	$(srcdir)/ui/ShareResource.hpp		\
	$(srcdir)/utils/Config.cpp		\
	$(srcdir)/utils/Config.hpp		\
	$(srcdir)/utils/Logger.cpp		\
	$(srcdir)/utils/Logger.hpp		\
	$(srcdir)/utils/UUID.cpp		\
	$(srcdir)/utils/UUID.hpp		\
	$(srcdir)/utils/Zip.cpp			\
	$(srcdir)/utils/Zip.hpp


# BOOST_NO_CXX11_SCOPED_ENUMS prevents a link error with outdated boost filesystem lib
fileshelter_CXXFLAGS=-std=c++11 -Wall -I$(srcdir)/ui -DBOOST_NO_CXX11_SCOPED_ENUMS $(libzip_CFLAGS)
fileshelter_LDADD=$(libzip_LIBS)

