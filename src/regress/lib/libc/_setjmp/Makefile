#	$OpenBSD: Makefile,v 1.2 2001/01/29 02:05:38 niklas Exp $
#	$NetBSD: Makefile,v 1.2 1995/04/20 22:38:44 cgd Exp $

PROG=	_setjmptest
SRCS=	jmptest.c

CFLAGS+= -DTEST_U_SETJMP

.PATH:	${.CURDIR}/../setjmp

.include <bsd.regress.mk>
