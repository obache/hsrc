# $NetBSD: Makefile,v 1.1 2020/04/18 12:50:44 js Exp $

DISTNAME=	signedjson-1.1
PKGNAME=	${PYPKGPREFIX}-${DISTNAME}
CATEGORIES=	security
MASTER_SITES=	${MASTER_SITE_PYPI:=s/signedjson/}

MAINTAINER=	js@pkgsrc.org
HOMEPAGE=	https://github.com/matrix-org/
COMMENT=	Signs JSON objects with ED25519 signatures
LICENSE=	apache-2.0

USE_LANGUAGES=	# none

DEPENDS+=	${PYPKGPREFIX}-canonicaljson>=1.0.0:../../devel/py-canonicaljson
DEPENDS+=	${PYPKGPREFIX}-unpaddedbase64>=1.0.1:../../devel/py-unpaddedbase64
DEPENDS+=	${PYPKGPREFIX}-nacl>=0.3.0:../../security/py-nacl
DEPENDS+=	${PYPKGPREFIX}-typing-extensions>=3.5:../../devel/py-typing-extensions

.include "../../lang/python/egg.mk"
.include "../../mk/bsd.pkg.mk"
