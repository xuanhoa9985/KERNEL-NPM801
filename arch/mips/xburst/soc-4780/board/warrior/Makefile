
obj-y += warrior-misc.o warrior-pm.o warrior-lcd.o  

obj-$(CONFIG_I2C)		+= warrior-i2c.o
obj-$(CONFIG_MFD_ACT8600)	+= warrior-regulator.o
obj-$(CONFIG_MMC_JZ4780)	+= warrior-mmc.o
obj-$(CONFIG_JZ4780_INTERNAL_CODEC) += warrior-sound.o
obj-$(CONFIG_NAND_JZ4780)	+= warrior-nand.o

ifeq ($(CONFIG_BOARD_TROOPER), y)
EXTRA_CFLAGS+=-DCONFIG_BOARD_WARRIOR_V_1_1
endif
