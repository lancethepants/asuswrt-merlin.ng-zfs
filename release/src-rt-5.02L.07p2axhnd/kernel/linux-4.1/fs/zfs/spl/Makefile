ifneq ($(KBUILD_EXTMOD),)
src = /home/lance/zfs-2.1.6/module/spl
obj = /home/lance/zfs-2.1.6/module/spl
mfdir = $(obj)
else
mfdir = $(srctree)/$(src)
endif

MODULE := spl

obj-$(CONFIG_ZFS) := $(MODULE).o

include $(mfdir)/../os/linux/spl/Makefile
