LIBRARY=lib/libtcore.a
TARGET= $(LIBRARY)
HOME=../
CINC=-Iinclude -Isource

include $(HOME)/build.mk

dep:
	@mkdir -p lib

install:
	mkdir -p $(PREFIX)
	cp -rf lib $(PREFIX)
	cp -rf include $(PREFIX)
	find $(PREFIX) -name "*.d" -or -name "*.o" | xargs rm -f
