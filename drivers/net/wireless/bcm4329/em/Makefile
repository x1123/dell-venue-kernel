#
# Makefile fragment for Linux 2.6
# Broadcom DHD Driver 4.218.248.12 MFG
#

obj-$(CONFIG_BCM4329) += dhd_test.o

dhd_test-objs = dhd_linux.o linux_osl.o bcmutils.o dhd_common.o dhd_custom_gpio.o siutils.o sbutils.o aiutils.o hndpmu.o dhd_linux_sched.o wl_iw.o bcmwifi.o dhd_cdc.o dhd_sdio.o bcmsdh_sdmmc.o bcmsdh.o bcmsdh_linux.o bcmsdh_sdmmc_linux.o

EXTRA_CFLAGS = -fshort-wchar -DLINUX -DSRCBASE=\".\" -DCONFIG_MMC_MSM7X00A -DBCMDRIVER -DBCMDONGLEHOST -DDHDTHREAD -DBCMWPA2 -DUNRELEASEDCHIP -DCONFIG_WIRELESS_EXT -DDHD_GPL -DDHD_SCHED -DDHD_SDALIGN=64 -DMAX_HDR_READ=64 -DDHD_FIRSTREAD=64 -DBDC -DTOE -DDHD_BCMEVENTS -DSHOW_EVENTS -DBCMSDIO -DDHD_GPL -DBCMLXSDMMC -DBCMPLATFORM_BUS -DSDIO_ISR_THREAD -Wall -Wstrict-prototypes -D__KERNEL__ -Dlinux -I. -I$(obj)/include -I$(obj)/shared -I$(obj)/dhd/sys -I$(obj)/dongle -I$(obj)/wl/sys


