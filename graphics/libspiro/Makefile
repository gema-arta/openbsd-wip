# $OpenBSD$

COMMENT =	simplifies the drawing of beautiful curves

V =		20190731
DISTNAME =	libspiro-${V}

SHARED_LIBS +=	spiro	0.0	# 1.0

CATEGORIES =	graphics

HOMEPAGE =	https://github.com/fontforge/libspiro

# GPLv3+
PERMIT_PACKAGE =	Yes

WANTLIB +=	m

MASTER_SITES =	https://github.com/fontforge/libspiro/releases/download/${V}/

USE_LIBTOOL =	gnu # unsupported option '--mode=link'

CONFIGURE_STYLE =	gnu

.include <bsd.port.mk>
