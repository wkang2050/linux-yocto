# SPDX-License-Identifier: GPL-2.0
#
# Makefile for Marvell's RVU Admin Function driver
#

ccflags-y += -I$(src)
obj-$(CONFIG_OCTEONTX2_MBOX) += rvu_mbox.o
obj-$(CONFIG_OCTEONTX2_AF) += rvu_af.o

rvu_mbox-y := mbox.o rvu_trace.o
rvu_af-y   := cgx.o rvu.o rvu_cgx.o rvu_npa.o rvu_nix.o rvu_nix_spi.o \
		  rvu_reg.o rvu_npc.o rvu_debugfs.o ptp.o \
		  rvu_validation.o rvu_sso.o rvu_tim.o \
		  rvu_cpt.o rvu_npc_fs.o rvu_fixes.o \
		  rvu_sdp.o rvu_ree.o rvu_cn10k.o rpm.o rvu_devlink.o \
		  rvu_switch.o mcs.o mcs_rvu_if.o mcs_cnf10kb.o mcs_fips.o \
		  rvu_npc_hash.o
