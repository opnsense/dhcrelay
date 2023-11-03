# $OpenBSD: Makefile,v 1.4 2017/04/05 14:43:14 reyk Exp $

.include <bsd.own.mk>

SRCS=	dhcrelay.c dispatch.c log.c bpf.c packet.c
PROG=	dhcrelay
MAN=	dhcrelay.8
WARNS=	3

CLEANFILES+=	.depend*

LOCALBASE?=${DESTDIR}/usr/local
PREFIX?=${LOCALBASE}

BINDIR=	${PREFIX}/sbin
MANDIR=	${PREFIX}/man/man

.include <bsd.prog.mk>
