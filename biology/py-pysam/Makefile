# Created by: Yuri Victorovich <yuri@rawbw.com>
# $FreeBSD$

PORTNAME=	pysam
PORTVERSION=	0.11.2.2
CATEGORIES=	biology python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	yuri@rawbw.com
COMMENT=	Python module for reading, manipulating and writing genomic data sets

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/COPYING

BUILD_DEPENDS=	cython:lang/cython
RUN_DEPENDS=	cython:lang/cython

USES=		gmake python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
