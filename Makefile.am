sbin_PROGRAMS = ssmtp
dist_man_MANS = \
		ssmtp.8 \
		ssmtp.conf.5

ssmtpconfdir = $(sysconfdir)/ssmtp
ssmtpconf_DATA = \
		 ssmtp.conf\
		 revaliases

ssmtp_SOURCES = \
		arpadate.c \
		base64.c \
		ssmtp.c \
		ssmtp.h \
		xgethostname.c \
		xgethostname.h

EXTRA_DIST = \
	     md5auth \
	     COPYRIGHT \
	     ssmtp.conf \
	     revaliases
