# $NetBSD: Makefile,v 1.37 2021/04/21 13:25:02 adam Exp $

DISTNAME=	ktux-15.08.3
PKGREVISION=	25
CATEGORIES=	misc
COMMENT=	Tux Screen Saver
MASTER_SITES=	${MASTER_SITE_KDE:=applications/15.08.3/src/}

.include "../../meta-pkgs/kde4/Makefile.kde4"

.include "../../meta-pkgs/kde4/kde4.mk"

.include "../../graphics/hicolor-icon-theme/buildlink3.mk"
.include "../../x11/kdelibs4/buildlink3.mk"
.include "../../x11/kde-workspace4/buildlink3.mk"

.include "../../mk/bsd.pkg.mk"
