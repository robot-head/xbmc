SRCS=ZeroconfAvahi.cpp \
     ZeroconfBrowserAvahi.cpp \
     ConnmanConnection.cpp \
     ConnmanNetworkManager.cpp \
     PosixConnection.cpp \
     PosixNetworkManager.cpp \

LIB=network_linux.a

include ../../../Makefile.include
-include $(patsubst %.cpp,%.P,$(patsubst %.c,%.P,$(SRCS)))
