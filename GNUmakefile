PROJECT=sh-x11-extra
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	install -D -t $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT) LICENSE
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/x-color          $(DESTDIR)$(PREFIX)/bin
	cp bin/x-search--openbsd $(DESTDIR)$(PREFIX)/bin
	cp bin/x-search--amazon $(DESTDIR)$(PREFIX)/bin
	cp bin/x-screenshot     $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
