#
# Makefile for the linux pstorefs routines.
#

obj-y += pstore.o

pstore-objs += inode.o platform.o
obj-$(CONFIG_PSTORE_FTRACE)	+= ftrace.o

pstore-$(CONFIG_PSTORE_PMSG)	+= pmsg.o
obj-$(CONFIG_PSTORE_PMSG_SSPLOG)	+= ss_platform_log.o

ramoops-objs += ram.o ram_core.o
obj-$(CONFIG_PSTORE_RAM)	+= ramoops.o
