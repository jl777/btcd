#############################################################################
# Makefile for building: testcoin-qt
# Generated by qmake (2.01a) (Qt 4.8.3) on: Wed Aug 27 21:10:05 2014
# Project:  testcoin-qt.pro
# Template: app
# Command: /usr/bin/qmake -o Makefile testcoin-qt.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_WEBKIT -DQT_GUI -DBOOST_THREAD_USE_LIB -DBOOST_SPIRIT_THREADSAFE -DUSE_UPNP=1 -DSTATICLIB -DHAVE_BUILD_INFO -DLINUX -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -m64 -pipe -O2 -D_REENTRANT -Wall -W $(DEFINES)
CXXFLAGS      = -m64 -pipe -fstack-protector-all --param ssp-buffer-size=1 -O2 -D_REENTRANT -fdiagnostics-show-option -Wall -Wextra -Wno-ignored-qualifiers -Wformat -Wformat-security -Wno-unused-parameter -Wstack-protector $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++-64 -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtGui -I/usr/include/qt4 -Isrc -Isrc/json -Isrc/qt -Isrc/leveldb/include -Isrc/leveldb/helpers -Ibuild -Ibuild
LINK          = g++
LFLAGS        = -m64 -fstack-protector-all --param ssp-buffer-size=1 -Wl,-O1
LIBS          = $(SUBLIBS)  -L/usr/lib/x86_64-linux-gnu -lminiupnpc /home/matthew/Desktop/dark-test-v2/src/src/leveldb/libleveldb.a /home/matthew/Desktop/dark-test-v2/src/src/leveldb/libmemenv.a -lssl -lcrypto -ldb_cxx -lboost_system -lboost_filesystem -lboost_program_options -lboost_thread -lrt -ldl -lpthread -lQtGui -lQtCore 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = build/

####### Files

SOURCES       = src/txdb-leveldb.cpp \
		src/qt/bitcoin.cpp \
		src/qt/bitcoingui.cpp \
		src/qt/transactiontablemodel.cpp \
		src/qt/addresstablemodel.cpp \
		src/qt/optionsdialog.cpp \
		src/qt/sendcoinsdialog.cpp \
		src/qt/coincontroldialog.cpp \
		src/qt/coincontroltreewidget.cpp \
		src/qt/addressbookpage.cpp \
		src/qt/signverifymessagedialog.cpp \
		src/qt/aboutdialog.cpp \
		src/qt/editaddressdialog.cpp \
		src/qt/bitcoinaddressvalidator.cpp \
		src/alert.cpp \
		src/version.cpp \
		src/sync.cpp \
		src/util.cpp \
		src/netbase.cpp \
		src/key.cpp \
		src/script.cpp \
		src/main.cpp \
		src/miner.cpp \
		src/init.cpp \
		src/net.cpp \
		src/irc.cpp \
		src/checkpoints.cpp \
		src/addrman.cpp \
		src/db.cpp \
		src/walletdb.cpp \
		src/qt/clientmodel.cpp \
		src/qt/guiutil.cpp \
		src/qt/transactionrecord.cpp \
		src/qt/optionsmodel.cpp \
		src/qt/monitoreddatamapper.cpp \
		src/qt/transactiondesc.cpp \
		src/qt/transactiondescdialog.cpp \
		src/qt/bitcoinstrings.cpp \
		src/qt/bitcoinamountfield.cpp \
		src/wallet.cpp \
		src/keystore.cpp \
		src/qt/transactionfilterproxy.cpp \
		src/qt/transactionview.cpp \
		src/qt/walletmodel.cpp \
		src/bitcoinrpc.cpp \
		src/rpcdump.cpp \
		src/rpcnet.cpp \
		src/rpcmining.cpp \
		src/rpcwallet.cpp \
		src/rpcblockchain.cpp \
		src/rpcrawtransaction.cpp \
		src/qt/overviewpage.cpp \
		src/qt/csvmodelwriter.cpp \
		src/crypter.cpp \
		src/qt/sendcoinsentry.cpp \
		src/qt/qvalidatedlineedit.cpp \
		src/qt/bitcoinunits.cpp \
		src/qt/qvaluecombobox.cpp \
		src/qt/askpassphrasedialog.cpp \
		src/protocol.cpp \
		src/qt/notificator.cpp \
		src/qt/qtipcserver.cpp \
		src/qt/rpcconsole.cpp \
		src/noui.cpp \
		src/kernel.cpp \
		src/scrypt-arm.S \
		src/scrypt-x86.S \
		src/scrypt-x86_64.S \
		src/scrypt.cpp \
		src/pbkdf2.cpp \
		src/zerocoin/Accumulator.cpp \
		src/zerocoin/AccumulatorProofOfKnowledge.cpp \
		src/zerocoin/Coin.cpp \
		src/zerocoin/CoinSpend.cpp \
		src/zerocoin/Commitment.cpp \
		src/zerocoin/ParamGeneration.cpp \
		src/zerocoin/Params.cpp \
		src/zerocoin/SerialNumberSignatureOfKnowledge.cpp \
		src/zerocoin/SpendMetaData.cpp \
		src/zerocoin/ZeroTest.cpp qrc_bitcoin.cpp
OBJECTS       = build/txdb-leveldb.o \
		build/bitcoin.o \
		build/bitcoingui.o \
		build/transactiontablemodel.o \
		build/addresstablemodel.o \
		build/optionsdialog.o \
		build/sendcoinsdialog.o \
		build/coincontroldialog.o \
		build/coincontroltreewidget.o \
		build/addressbookpage.o \
		build/signverifymessagedialog.o \
		build/aboutdialog.o \
		build/editaddressdialog.o \
		build/bitcoinaddressvalidator.o \
		build/alert.o \
		build/version.o \
		build/sync.o \
		build/util.o \
		build/netbase.o \
		build/key.o \
		build/script.o \
		build/main.o \
		build/miner.o \
		build/init.o \
		build/net.o \
		build/irc.o \
		build/checkpoints.o \
		build/addrman.o \
		build/db.o \
		build/walletdb.o \
		build/clientmodel.o \
		build/guiutil.o \
		build/transactionrecord.o \
		build/optionsmodel.o \
		build/monitoreddatamapper.o \
		build/transactiondesc.o \
		build/transactiondescdialog.o \
		build/bitcoinstrings.o \
		build/bitcoinamountfield.o \
		build/wallet.o \
		build/keystore.o \
		build/transactionfilterproxy.o \
		build/transactionview.o \
		build/walletmodel.o \
		build/bitcoinrpc.o \
		build/rpcdump.o \
		build/rpcnet.o \
		build/rpcmining.o \
		build/rpcwallet.o \
		build/rpcblockchain.o \
		build/rpcrawtransaction.o \
		build/overviewpage.o \
		build/csvmodelwriter.o \
		build/crypter.o \
		build/sendcoinsentry.o \
		build/qvalidatedlineedit.o \
		build/bitcoinunits.o \
		build/qvaluecombobox.o \
		build/askpassphrasedialog.o \
		build/protocol.o \
		build/notificator.o \
		build/qtipcserver.o \
		build/rpcconsole.o \
		build/noui.o \
		build/kernel.o \
		build/scrypt-arm.o \
		build/scrypt-x86.o \
		build/scrypt-x86_64.o \
		build/scrypt.o \
		build/pbkdf2.o \
		build/Accumulator.o \
		build/AccumulatorProofOfKnowledge.o \
		build/Coin.o \
		build/CoinSpend.o \
		build/Commitment.o \
		build/ParamGeneration.o \
		build/Params.o \
		build/SerialNumberSignatureOfKnowledge.o \
		build/SpendMetaData.o \
		build/ZeroTest.o \
		build/qrc_bitcoin.o
DIST          = /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		testcoin-qt.pro
QMAKE_TARGET  = testcoin-qt
DESTDIR       = 
TARGET        = testcoin-qt

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): /home/matthew/Desktop/dark-test-v2/src/src/leveldb/libleveldb.a /home/matthew/Desktop/dark-test-v2/src/build/build.h build/ui_coincontroldialog.h build/ui_sendcoinsdialog.h build/ui_addressbookpage.h build/ui_signverifymessagedialog.h build/ui_aboutdialog.h build/ui_editaddressdialog.h build/ui_transactiondescdialog.h build/ui_overviewpage.h build/ui_sendcoinsentry.h build/ui_askpassphrasedialog.h build/ui_rpcconsole.h build/ui_optionsdialog.h $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: testcoin-qt.pro  /usr/share/qt4/mkspecs/linux-g++-64/qmake.conf /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/lib/x86_64-linux-gnu/libQtGui.prl \
		/usr/lib/x86_64-linux-gnu/libQtCore.prl
	$(QMAKE) -o Makefile testcoin-qt.pro
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/common/gcc-base.conf:
/usr/share/qt4/mkspecs/common/gcc-base-unix.conf:
/usr/share/qt4/mkspecs/common/g++-base.conf:
/usr/share/qt4/mkspecs/common/g++-unix.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/release.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/lib/x86_64-linux-gnu/libQtGui.prl:
/usr/lib/x86_64-linux-gnu/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -o Makefile testcoin-qt.pro

dist: 
	@$(CHK_DIR_EXISTS) build/testcoin-qt1.0.7 || $(MKDIR) build/testcoin-qt1.0.7 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) build/testcoin-qt1.0.7/ && $(COPY_FILE) --parents src/qt/bitcoingui.h src/qt/transactiontablemodel.h src/qt/addresstablemodel.h src/qt/optionsdialog.h src/qt/coincontroldialog.h src/qt/coincontroltreewidget.h src/qt/sendcoinsdialog.h src/qt/addressbookpage.h src/qt/signverifymessagedialog.h src/qt/aboutdialog.h src/qt/editaddressdialog.h src/qt/bitcoinaddressvalidator.h src/alert.h src/addrman.h src/base58.h src/bignum.h src/checkpoints.h src/compat.h src/coincontrol.h src/sync.h src/util.h src/uint256.h src/kernel.h src/scrypt.h src/pbkdf2.h src/zerocoin/Accumulator.h src/zerocoin/AccumulatorProofOfKnowledge.h src/zerocoin/Coin.h src/zerocoin/CoinSpend.h src/zerocoin/Commitment.h src/zerocoin/ParamGeneration.h src/zerocoin/Params.h src/zerocoin/SerialNumberSignatureOfKnowledge.h src/zerocoin/SpendMetaData.h src/zerocoin/ZeroTest.h src/zerocoin/Zerocoin.h src/serialize.h src/strlcpy.h src/main.h src/miner.h src/net.h src/key.h src/db.h src/txdb.h src/walletdb.h src/script.h src/init.h src/irc.h src/mruset.h src/json/json_spirit_writer_template.h src/json/json_spirit_writer.h src/json/json_spirit_value.h src/json/json_spirit_utils.h src/json/json_spirit_stream_reader.h src/json/json_spirit_reader_template.h src/json/json_spirit_reader.h src/json/json_spirit_error_position.h src/json/json_spirit.h src/qt/clientmodel.h src/qt/guiutil.h src/qt/transactionrecord.h src/qt/guiconstants.h src/qt/optionsmodel.h src/qt/monitoreddatamapper.h src/qt/transactiondesc.h src/qt/transactiondescdialog.h src/qt/bitcoinamountfield.h src/wallet.h src/keystore.h src/qt/transactionfilterproxy.h src/qt/transactionview.h src/qt/walletmodel.h src/bitcoinrpc.h src/qt/overviewpage.h src/qt/csvmodelwriter.h src/crypter.h src/qt/sendcoinsentry.h src/qt/qvalidatedlineedit.h src/qt/bitcoinunits.h src/qt/qvaluecombobox.h src/qt/askpassphrasedialog.h src/protocol.h src/qt/notificator.h src/qt/qtipcserver.h src/allocators.h src/ui_interface.h src/qt/rpcconsole.h src/version.h src/netbase.h src/clientversion.h build/testcoin-qt1.0.7/ && $(COPY_FILE) --parents src/qt/bitcoin.qrc build/testcoin-qt1.0.7/ && $(COPY_FILE) --parents src/txdb-leveldb.cpp src/qt/bitcoin.cpp src/qt/bitcoingui.cpp src/qt/transactiontablemodel.cpp src/qt/addresstablemodel.cpp src/qt/optionsdialog.cpp src/qt/sendcoinsdialog.cpp src/qt/coincontroldialog.cpp src/qt/coincontroltreewidget.cpp src/qt/addressbookpage.cpp src/qt/signverifymessagedialog.cpp src/qt/aboutdialog.cpp src/qt/editaddressdialog.cpp src/qt/bitcoinaddressvalidator.cpp src/alert.cpp src/version.cpp src/sync.cpp src/util.cpp src/netbase.cpp src/key.cpp src/script.cpp src/main.cpp src/miner.cpp src/init.cpp src/net.cpp src/irc.cpp src/checkpoints.cpp src/addrman.cpp src/db.cpp src/walletdb.cpp src/qt/clientmodel.cpp src/qt/guiutil.cpp src/qt/transactionrecord.cpp src/qt/optionsmodel.cpp src/qt/monitoreddatamapper.cpp src/qt/transactiondesc.cpp src/qt/transactiondescdialog.cpp src/qt/bitcoinstrings.cpp src/qt/bitcoinamountfield.cpp src/wallet.cpp src/keystore.cpp src/qt/transactionfilterproxy.cpp src/qt/transactionview.cpp src/qt/walletmodel.cpp src/bitcoinrpc.cpp src/rpcdump.cpp src/rpcnet.cpp src/rpcmining.cpp src/rpcwallet.cpp src/rpcblockchain.cpp src/rpcrawtransaction.cpp src/qt/overviewpage.cpp src/qt/csvmodelwriter.cpp src/crypter.cpp src/qt/sendcoinsentry.cpp src/qt/qvalidatedlineedit.cpp src/qt/bitcoinunits.cpp src/qt/qvaluecombobox.cpp src/qt/askpassphrasedialog.cpp src/protocol.cpp src/qt/notificator.cpp src/qt/qtipcserver.cpp src/qt/rpcconsole.cpp src/noui.cpp src/kernel.cpp src/scrypt-arm.S src/scrypt-x86.S src/scrypt-x86_64.S src/scrypt.cpp src/pbkdf2.cpp src/zerocoin/Accumulator.cpp src/zerocoin/AccumulatorProofOfKnowledge.cpp src/zerocoin/Coin.cpp src/zerocoin/CoinSpend.cpp src/zerocoin/Commitment.cpp src/zerocoin/ParamGeneration.cpp src/zerocoin/Params.cpp src/zerocoin/SerialNumberSignatureOfKnowledge.cpp src/zerocoin/SpendMetaData.cpp src/zerocoin/ZeroTest.cpp build/testcoin-qt1.0.7/ && $(COPY_FILE) --parents src/qt/forms/coincontroldialog.ui src/qt/forms/sendcoinsdialog.ui src/qt/forms/addressbookpage.ui src/qt/forms/signverifymessagedialog.ui src/qt/forms/aboutdialog.ui src/qt/forms/editaddressdialog.ui src/qt/forms/transactiondescdialog.ui src/qt/forms/overviewpage.ui src/qt/forms/sendcoinsentry.ui src/qt/forms/askpassphrasedialog.ui src/qt/forms/rpcconsole.ui src/qt/forms/optionsdialog.ui build/testcoin-qt1.0.7/ && (cd `dirname build/testcoin-qt1.0.7` && $(TAR) testcoin-qt1.0.7.tar testcoin-qt1.0.7 && $(COMPRESS) testcoin-qt1.0.7.tar) && $(MOVE) `dirname build/testcoin-qt1.0.7`/testcoin-qt1.0.7.tar.gz . && $(DEL_FILE) -r build/testcoin-qt1.0.7


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) /home/matthew/Desktop/dark-test-v2/src/src/leveldb/libleveldb.a; cd /home/matthew/Desktop/dark-test-v2/src/src/leveldb ; $(MAKE) clean
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


/home/matthew/Desktop/dark-test-v2/src/src/leveldb/libleveldb.a: FORCE
	cd /home/matthew/Desktop/dark-test-v2/src/src/leveldb && CC=gcc CXX=g++ $(MAKE) OPT="-m64 -pipe -fstack-protector-all --param ssp-buffer-size=1 -O2" libleveldb.a libmemenv.a

/home/matthew/Desktop/dark-test-v2/src/build/build.h: FORCE
	cd /home/matthew/Desktop/dark-test-v2/src; /bin/sh share/genbuild.sh /home/matthew/Desktop/dark-test-v2/src/build/build.h

check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_TSQM_make_all:
compiler_TSQM_clean:
compiler_moc_header_make_all:
compiler_moc_header_clean:
compiler_rcc_make_all: qrc_bitcoin.cpp
compiler_rcc_clean:
	-$(DEL_FILE) qrc_bitcoin.cpp
qrc_bitcoin.cpp: src/qt/bitcoin.qrc
	/usr/bin/rcc -name bitcoin src/qt/bitcoin.qrc -o qrc_bitcoin.cpp

compiler_image_collection_make_all: build/qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) build/qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: build/ui_coincontroldialog.h build/ui_sendcoinsdialog.h build/ui_addressbookpage.h build/ui_signverifymessagedialog.h build/ui_aboutdialog.h build/ui_editaddressdialog.h build/ui_transactiondescdialog.h build/ui_overviewpage.h build/ui_sendcoinsentry.h build/ui_askpassphrasedialog.h build/ui_rpcconsole.h build/ui_optionsdialog.h
compiler_uic_clean:
	-$(DEL_FILE) build/ui_coincontroldialog.h build/ui_sendcoinsdialog.h build/ui_addressbookpage.h build/ui_signverifymessagedialog.h build/ui_aboutdialog.h build/ui_editaddressdialog.h build/ui_transactiondescdialog.h build/ui_overviewpage.h build/ui_sendcoinsentry.h build/ui_askpassphrasedialog.h build/ui_rpcconsole.h build/ui_optionsdialog.h
build/ui_coincontroldialog.h: src/qt/forms/coincontroldialog.ui
	/usr/bin/uic-qt4 src/qt/forms/coincontroldialog.ui -o build/ui_coincontroldialog.h

build/ui_sendcoinsdialog.h: src/qt/forms/sendcoinsdialog.ui
	/usr/bin/uic-qt4 src/qt/forms/sendcoinsdialog.ui -o build/ui_sendcoinsdialog.h

build/ui_addressbookpage.h: src/qt/forms/addressbookpage.ui
	/usr/bin/uic-qt4 src/qt/forms/addressbookpage.ui -o build/ui_addressbookpage.h

build/ui_signverifymessagedialog.h: src/qt/forms/signverifymessagedialog.ui
	/usr/bin/uic-qt4 src/qt/forms/signverifymessagedialog.ui -o build/ui_signverifymessagedialog.h

build/ui_aboutdialog.h: src/qt/forms/aboutdialog.ui
	/usr/bin/uic-qt4 src/qt/forms/aboutdialog.ui -o build/ui_aboutdialog.h

build/ui_editaddressdialog.h: src/qt/forms/editaddressdialog.ui
	/usr/bin/uic-qt4 src/qt/forms/editaddressdialog.ui -o build/ui_editaddressdialog.h

build/ui_transactiondescdialog.h: src/qt/forms/transactiondescdialog.ui
	/usr/bin/uic-qt4 src/qt/forms/transactiondescdialog.ui -o build/ui_transactiondescdialog.h

build/ui_overviewpage.h: src/qt/forms/overviewpage.ui
	/usr/bin/uic-qt4 src/qt/forms/overviewpage.ui -o build/ui_overviewpage.h

build/ui_sendcoinsentry.h: src/qt/forms/sendcoinsentry.ui
	/usr/bin/uic-qt4 src/qt/forms/sendcoinsentry.ui -o build/ui_sendcoinsentry.h

build/ui_askpassphrasedialog.h: src/qt/forms/askpassphrasedialog.ui
	/usr/bin/uic-qt4 src/qt/forms/askpassphrasedialog.ui -o build/ui_askpassphrasedialog.h

build/ui_rpcconsole.h: src/qt/forms/rpcconsole.ui
	/usr/bin/uic-qt4 src/qt/forms/rpcconsole.ui -o build/ui_rpcconsole.h

build/ui_optionsdialog.h: src/qt/forms/optionsdialog.ui
	/usr/bin/uic-qt4 src/qt/forms/optionsdialog.ui -o build/ui_optionsdialog.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_rcc_clean compiler_uic_clean 

####### Compile

build/txdb-leveldb.o: src/txdb-leveldb.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/txdb-leveldb.o src/txdb-leveldb.cpp

build/bitcoin.o: src/qt/bitcoin.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoin.o src/qt/bitcoin.cpp

build/bitcoingui.o: src/qt/bitcoingui.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoingui.o src/qt/bitcoingui.cpp

build/transactiontablemodel.o: src/qt/transactiontablemodel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/transactiontablemodel.o src/qt/transactiontablemodel.cpp

build/addresstablemodel.o: src/qt/addresstablemodel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/addresstablemodel.o src/qt/addresstablemodel.cpp

build/optionsdialog.o: src/qt/optionsdialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/optionsdialog.o src/qt/optionsdialog.cpp

build/sendcoinsdialog.o: src/qt/sendcoinsdialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/sendcoinsdialog.o src/qt/sendcoinsdialog.cpp

build/coincontroldialog.o: src/qt/coincontroldialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/coincontroldialog.o src/qt/coincontroldialog.cpp

build/coincontroltreewidget.o: src/qt/coincontroltreewidget.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/coincontroltreewidget.o src/qt/coincontroltreewidget.cpp

build/addressbookpage.o: src/qt/addressbookpage.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/addressbookpage.o src/qt/addressbookpage.cpp

build/signverifymessagedialog.o: src/qt/signverifymessagedialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/signverifymessagedialog.o src/qt/signverifymessagedialog.cpp

build/aboutdialog.o: src/qt/aboutdialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/aboutdialog.o src/qt/aboutdialog.cpp

build/editaddressdialog.o: src/qt/editaddressdialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/editaddressdialog.o src/qt/editaddressdialog.cpp

build/bitcoinaddressvalidator.o: src/qt/bitcoinaddressvalidator.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoinaddressvalidator.o src/qt/bitcoinaddressvalidator.cpp

build/alert.o: src/alert.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/alert.o src/alert.cpp

build/version.o: src/version.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/version.o src/version.cpp

build/sync.o: src/sync.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/sync.o src/sync.cpp

build/util.o: src/util.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/util.o src/util.cpp

build/netbase.o: src/netbase.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/netbase.o src/netbase.cpp

build/key.o: src/key.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/key.o src/key.cpp

build/script.o: src/script.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/script.o src/script.cpp

build/main.o: src/main.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/main.o src/main.cpp

build/miner.o: src/miner.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/miner.o src/miner.cpp

build/init.o: src/init.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/init.o src/init.cpp

build/net.o: src/net.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/net.o src/net.cpp

build/irc.o: src/irc.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/irc.o src/irc.cpp

build/checkpoints.o: src/checkpoints.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/checkpoints.o src/checkpoints.cpp

build/addrman.o: src/addrman.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/addrman.o src/addrman.cpp

build/db.o: src/db.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/db.o src/db.cpp

build/walletdb.o: src/walletdb.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/walletdb.o src/walletdb.cpp

build/clientmodel.o: src/qt/clientmodel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/clientmodel.o src/qt/clientmodel.cpp

build/guiutil.o: src/qt/guiutil.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/guiutil.o src/qt/guiutil.cpp

build/transactionrecord.o: src/qt/transactionrecord.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/transactionrecord.o src/qt/transactionrecord.cpp

build/optionsmodel.o: src/qt/optionsmodel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/optionsmodel.o src/qt/optionsmodel.cpp

build/monitoreddatamapper.o: src/qt/monitoreddatamapper.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/monitoreddatamapper.o src/qt/monitoreddatamapper.cpp

build/transactiondesc.o: src/qt/transactiondesc.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/transactiondesc.o src/qt/transactiondesc.cpp

build/transactiondescdialog.o: src/qt/transactiondescdialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/transactiondescdialog.o src/qt/transactiondescdialog.cpp

build/bitcoinstrings.o: src/qt/bitcoinstrings.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoinstrings.o src/qt/bitcoinstrings.cpp

build/bitcoinamountfield.o: src/qt/bitcoinamountfield.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoinamountfield.o src/qt/bitcoinamountfield.cpp

build/wallet.o: src/wallet.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/wallet.o src/wallet.cpp

build/keystore.o: src/keystore.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/keystore.o src/keystore.cpp

build/transactionfilterproxy.o: src/qt/transactionfilterproxy.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/transactionfilterproxy.o src/qt/transactionfilterproxy.cpp

build/transactionview.o: src/qt/transactionview.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/transactionview.o src/qt/transactionview.cpp

build/walletmodel.o: src/qt/walletmodel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/walletmodel.o src/qt/walletmodel.cpp

build/bitcoinrpc.o: src/bitcoinrpc.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoinrpc.o src/bitcoinrpc.cpp

build/rpcdump.o: src/rpcdump.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcdump.o src/rpcdump.cpp

build/rpcnet.o: src/rpcnet.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcnet.o src/rpcnet.cpp

build/rpcmining.o: src/rpcmining.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcmining.o src/rpcmining.cpp

build/rpcwallet.o: src/rpcwallet.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcwallet.o src/rpcwallet.cpp

build/rpcblockchain.o: src/rpcblockchain.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcblockchain.o src/rpcblockchain.cpp

build/rpcrawtransaction.o: src/rpcrawtransaction.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcrawtransaction.o src/rpcrawtransaction.cpp

build/overviewpage.o: src/qt/overviewpage.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/overviewpage.o src/qt/overviewpage.cpp

build/csvmodelwriter.o: src/qt/csvmodelwriter.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/csvmodelwriter.o src/qt/csvmodelwriter.cpp

build/crypter.o: src/crypter.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/crypter.o src/crypter.cpp

build/sendcoinsentry.o: src/qt/sendcoinsentry.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/sendcoinsentry.o src/qt/sendcoinsentry.cpp

build/qvalidatedlineedit.o: src/qt/qvalidatedlineedit.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/qvalidatedlineedit.o src/qt/qvalidatedlineedit.cpp

build/bitcoinunits.o: src/qt/bitcoinunits.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/bitcoinunits.o src/qt/bitcoinunits.cpp

build/qvaluecombobox.o: src/qt/qvaluecombobox.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/qvaluecombobox.o src/qt/qvaluecombobox.cpp

build/askpassphrasedialog.o: src/qt/askpassphrasedialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/askpassphrasedialog.o src/qt/askpassphrasedialog.cpp

build/protocol.o: src/protocol.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/protocol.o src/protocol.cpp

build/notificator.o: src/qt/notificator.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/notificator.o src/qt/notificator.cpp

build/qtipcserver.o: src/qt/qtipcserver.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/qtipcserver.o src/qt/qtipcserver.cpp

build/rpcconsole.o: src/qt/rpcconsole.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/rpcconsole.o src/qt/rpcconsole.cpp

build/noui.o: src/noui.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/noui.o src/noui.cpp

build/kernel.o: src/kernel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/kernel.o src/kernel.cpp

build/scrypt-arm.o: src/scrypt-arm.S 
	$(CC) -c $(CFLAGS) $(INCPATH) -o build/scrypt-arm.o src/scrypt-arm.S

build/scrypt-x86.o: src/scrypt-x86.S 
	$(CC) -c $(CFLAGS) $(INCPATH) -o build/scrypt-x86.o src/scrypt-x86.S

build/scrypt-x86_64.o: src/scrypt-x86_64.S 
	$(CC) -c $(CFLAGS) $(INCPATH) -o build/scrypt-x86_64.o src/scrypt-x86_64.S

build/scrypt.o: src/scrypt.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/scrypt.o src/scrypt.cpp

build/pbkdf2.o: src/pbkdf2.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/pbkdf2.o src/pbkdf2.cpp

build/Accumulator.o: src/zerocoin/Accumulator.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/Accumulator.o src/zerocoin/Accumulator.cpp

build/AccumulatorProofOfKnowledge.o: src/zerocoin/AccumulatorProofOfKnowledge.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/AccumulatorProofOfKnowledge.o src/zerocoin/AccumulatorProofOfKnowledge.cpp

build/Coin.o: src/zerocoin/Coin.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/Coin.o src/zerocoin/Coin.cpp

build/CoinSpend.o: src/zerocoin/CoinSpend.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/CoinSpend.o src/zerocoin/CoinSpend.cpp

build/Commitment.o: src/zerocoin/Commitment.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/Commitment.o src/zerocoin/Commitment.cpp

build/ParamGeneration.o: src/zerocoin/ParamGeneration.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/ParamGeneration.o src/zerocoin/ParamGeneration.cpp

build/Params.o: src/zerocoin/Params.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/Params.o src/zerocoin/Params.cpp

build/SerialNumberSignatureOfKnowledge.o: src/zerocoin/SerialNumberSignatureOfKnowledge.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/SerialNumberSignatureOfKnowledge.o src/zerocoin/SerialNumberSignatureOfKnowledge.cpp

build/SpendMetaData.o: src/zerocoin/SpendMetaData.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/SpendMetaData.o src/zerocoin/SpendMetaData.cpp

build/ZeroTest.o: src/zerocoin/ZeroTest.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/ZeroTest.o src/zerocoin/ZeroTest.cpp

build/qrc_bitcoin.o: qrc_bitcoin.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o build/qrc_bitcoin.o qrc_bitcoin.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

