# $NetBSD: Makefile,v 1.149 2021/05/25 07:29:41 nia Exp $

.include "../../graphics/cairo/Makefile.common"

PKGREVISION=	4

TEST_TARGET=			check

.include "options.mk"

.include "../../archivers/lzo/buildlink3.mk"
.include "../../devel/zlib/buildlink3.mk"
.include "../../fonts/fontconfig/buildlink3.mk"
.include "../../graphics/freetype2/buildlink3.mk"
.include "../../graphics/png/buildlink3.mk"
# include?
#.include "../../print/libspectre/buildlink3.mk"
BUILDLINK_API_DEPENDS.pixman+=	pixman>=0.30.0
.include "../../x11/pixman/buildlink3.mk"
.include "../../mk/pthread.buildlink3.mk"
.include "../../mk/bsd.pkg.mk"
