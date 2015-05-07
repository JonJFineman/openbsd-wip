# $OpenBSD$

COMMENT =	python interface to OpenStack Nova API

MODPY_EGG_VERSION = 2.24.1
DISTNAME =	python-novaclient-${MODPY_EGG_VERSION}
PKGNAME = 	py-novaclient-${MODPY_EGG_VERSION}
CATEGORIES =	net

HOMEPAGE =	https://git.openstack.org/cgit/openstack/python-novaclient
MODPY_PI =	Yes

# Apache 2.0
PERMIT_PACKAGE_CDROM =	Yes

MODULES =		lang/python
MODPY_SETUPTOOLS =	Yes

RUN_DEPENDS =		textproc/py-prettytable \
			www/py-httplib2

BUILD_DEPENDS =		${RUN_DEPENDS}

# XXX Haven't looked yet into what tests do
#NO_TEST =		Yes

#post-extract:
#	@perl -pi -e 's,setup_requires.*,,' ${WRKSRC}/setup.py

.include <bsd.port.mk>