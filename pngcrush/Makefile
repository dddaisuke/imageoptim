.PHONY: all

all: pngcrush.c

pngcrush.c:
	curl -L http://downloads.sourceforge.net/project/pmt/pngcrush/1.7.44/pngcrush-1.7.44.tar.gz | tar xj --strip-components=1 --exclude=Makefile
	-rm png.h pngconf.h 2>/dev/null

clean:
	-rm *.c *.h 2>/dev/null

install: