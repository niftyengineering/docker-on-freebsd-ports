# $FreeBSD$

PORTNAME=	runc-devel

GO_TARGET=      ./runc:${PREFIX}/sbin/runc-devel
PORTVERSION=	2019112601
DISTVERSIONPREFIX=	v
CATEGORIES=	sysutils

MAINTAINER=	heliocentric@gmail.com
COMMENT=	blah blah blah

LICENSE=	MPL20
LICENSE_FILE=	${WRKSRC}/LICENSE

USES=           go:modules
USE_GITHUB=	yes
GH_ACCOUNT=	niftyengineering
GH_TAGNAME=     b5218c702a1782f68d5ba50033e2f0788ccb735a
GH_PROJECT=     runc

GH_TUPLE=	\
		Sirupsen:logrus:26709e271410:sirupsen_logrus/vendor/github.com/Sirupsen/logrus \
		coreos:go-systemd:48702e0da86b:coreos_go_systemd/vendor/github.com/coreos/go-systemd \
		coreos:pkg:3ac0863d7acf:coreos_pkg/vendor/github.com/coreos/pkg \
		docker:docker:0f5c9d301b9b:docker_docker/vendor/github.com/docker/docker \
		docker:go-units:v0.2.0:docker_go_units/vendor/github.com/docker/go-units \
		godbus:dbus:c7fdd8b5cd55:godbus_dbus/vendor/github.com/godbus/dbus \
		golang:protobuf:18c9bb326172:golang_protobuf/vendor/github.com/golang/protobuf \
		golang:sys:fb4cac33e319:golang_sys/vendor/golang.org/x/sys \
		mrunalp:fileutils:ed869b029674:mrunalp_fileutils/vendor/github.com/mrunalp/fileutils \
		opencontainers:runtime-spec:198f23f827ee:opencontainers_runtime_spec/vendor/github.com/opencontainers/runtime-spec \
		opencontainers:selinux:v1.0.0-rc1:opencontainers_selinux/vendor/github.com/opencontainers/selinux \
		seccomp:libseccomp-golang:32f571b70023:seccomp_libseccomp_golang/vendor/github.com/seccomp/libseccomp-golang \
		syndtr:gocapability:e7cb7fa329f4:syndtr_gocapability/vendor/github.com/syndtr/gocapability \
		urfave:cli:d53eb991652b:urfave_cli/vendor/github.com/urfave/cli \
		vishvananda:netlink:1e2e08e8a2dc:vishvananda_netlink/vendor/github.com/vishvananda/netlink


.include <bsd.port.mk>

