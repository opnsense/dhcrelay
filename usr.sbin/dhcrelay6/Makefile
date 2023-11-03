# $OpenBSD: Makefile,v 1.2 2017/04/16 00:52:54 aoyama Exp $

.include <bsd.own.mk>

SRCS=	dhcrelay6.c dispatch.c log.c bpf.c packet.c
PROG=	dhcrelay6
MAN=	dhcrelay6.8
WARNS=	3

CLEANFILES=	.depend*

LOCALBASE?=${DESTDIR}/usr/local
PREFIX?=${LOCALBASE}

BINDIR=	${PREFIX}/sbin
MANDIR=	${PREFIX}/man/man

.include <bsd.prog.mk>
