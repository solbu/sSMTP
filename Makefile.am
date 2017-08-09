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

if MD5AUTH
ssmtp_SOURCES += \
		md5auth/md5c.c \
		md5auth/hmac_md5.c
endif


EXTRA_DIST = \
	     md5auth \
	     COPYRIGHT \
	     ssmtp.conf \
	     revaliases
