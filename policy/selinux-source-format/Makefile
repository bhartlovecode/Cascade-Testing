SBINDIR := /usr/sbin
BINDIR := /usr/bin
MAKEFILE := /usr/share/selinux/devel/Makefile

all:
	$(BINDIR)/make -f $(MAKEFILE)

install: all
	$(SBINDIR)/semodule -i myapp.pp
	$(SBINDIR)/restorecon -RF /usr/local/src/ /opt/anaconda3/bin/
