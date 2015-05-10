EXTRA_DIST = \
	basepop-gtk-theme \
	basepop-light-gtk-theme \
	CREDITS \
	LICENSE \
	README.md

xsessiondir = $(datadir)/xsessions

themedir = $(datadir)/themes

install-data-hook:
	$(MKDIR_P) $(DESTDIR)/usr/share/themes
	cp -Rv basepop-gtk-theme $(DESTDIR)/usr/share/themes/.
	cp -Rv basepop-light-gtk-theme $(DESTDIR)/usr/share/themes/.

uninstall-hook:
	test -e $(DESTDIR)/usr/share/themes/basepop-gtk-theme && rm -rfv $(DESTDIR)/usr/share/themes/basepop-gtk-theme
	test -e $(DESTDIR)/usr/share/themes/basepop-light-gtk-theme && rm -rfv $(DESTDIR)/usr/share/themes/basepop-light-gtk-theme
