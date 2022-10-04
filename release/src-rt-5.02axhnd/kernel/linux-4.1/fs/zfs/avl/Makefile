ifneq ($(KBUILD_EXTMOD),)
src = /home/lance/zfs-2.1.6/module/avl
obj = /home/lance/zfs-2.1.6/module/avl
endif

MODULE := zavl

obj-$(CONFIG_ZFS) := $(MODULE).o

$(MODULE)-objs += avl.o
