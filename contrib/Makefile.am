##
##  $Id: Makefile.am,v 1.12 2005/04/25 15:58:01 bboy Exp $
##

EXTRA_DIST	=	README README.alias admin.php create_domain.pl mydns.redhat stats.php mydns.solaris MyDNS.pm mydns.service

if HAVE_SYSTEMD
    systemdsystemunit_DATA = mydns.service
endif

ctags:
	ctags *.php


## vi:set ts=3:
