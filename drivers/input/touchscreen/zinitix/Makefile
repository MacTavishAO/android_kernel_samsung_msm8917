#
# Makefile for the Zinitix Touchscreen driver
#

obj-$(CONFIG_TOUCHSCREEN_ZINITIX_BT532)	+= zinitix_bt532_ts.o
obj-$(CONFIG_TOUCHSCREEN_ZINITIX_BT431)	+= zinitix_bt532_ts.o
obj-$(CONFIG_TOUCHSCREEN_ZINITIX_ZT75XX)	+= zinitix_bt532_ts.o

ifeq ($(CONFIG_INPUT_TOUCHSCREEN_TCLMV2), y)
obj-$(CONFIG_TOUCHSCREEN_ZINITIX_ZT75XX_TCLM)	+= zinitix_zt75xx_ts_tclmv2.o
else
obj-$(CONFIG_TOUCHSCREEN_ZINITIX_ZT75XX_TCLM)	+= zinitix_zt75xx_ts.o
endif
