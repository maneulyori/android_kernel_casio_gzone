#/**********************************************************************
#* File Name: drivers/media/video/msm/eeprom/Makefile
#* 
#* (C) NEC CASIO Mobile Communications, Ltd. 2013
#**********************************************************************/
GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
EXTRA_CFLAGS += -Idrivers/media/video/msm/io
obj-$(CONFIG_MSM_EEPROM) += msm_camera_eeprom.o
obj-$(CONFIG_IMX074_EEPROM) += imx074_eeprom.o
obj-$(CONFIG_IMX091_EEPROM) += imx091_eeprom.o
obj-$(CONFIG_MT9E013_EEPROM) += mt9e013_eeprom.o
