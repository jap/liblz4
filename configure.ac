AC_INIT([liblz4], [0.1], [spaans@gmail.com], [lz4],
        [http://jasper.es/lz4])
AM_INIT_AUTOMAKE([1.10 -Wall no-define])
AC_PROG_CC

LT_INIT([disable-static])
AC_SUBST([LZ4_SO_VERSION], [1:0:0])
AC_SUBST([LZ4_API_VERSION], [1.0])

AC_CONFIG_FILES([Makefile
                 lz4-${LZ4_API_VERSION}.pc:lz4.pc.in])
AC_OUTPUT
