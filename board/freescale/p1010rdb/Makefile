#
# Copyright 2010-2011 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#

MINIMAL=

ifdef CONFIG_SPL_BUILD
ifdef CONFIG_SPL_INIT_MINIMAL
MINIMAL=y
endif
endif

ifdef MINIMAL

obj-y	+= spl_minimal.o tlb.o law.o

else

obj-y	+= p1010rdb.o
obj-y	+= ddr.o
obj-y	+= law.o
obj-y	+= tlb.o

endif
