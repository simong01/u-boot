#
# Copyright 2024 Ezurio LLC
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += imx91_tap2id.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_TARGET_IMX91_TAP2ID) += lpddr4_timing.o
endif
