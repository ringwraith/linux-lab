_BASE    = 1
ARCH     = x86
XARCH    = i386
CPU     ?= i686
MEM     ?= 128M
QEMU    ?= v0.10.6
SMP     ?= 2
LINUX   ?= v5.1
BUILDROOT?= 2019.02.2
NETDEV  ?= ne2k_pci
SERIAL  ?= ttyS0
ORIIMG  ?= arch/$(ARCH)/boot/bzImage
ROOTDEV ?= /dev/ram0
#CCPRE   = i686-pc-linux-gnu-
KIMAGE  ?= $(PREBUILT_KERNEL)/$(XARCH)/$(MACH)/$(LINUX)/bzImage
ROOTFS  ?= $(PREBUILT_ROOT)/$(XARCH)/$(CPU)/rootfs.cpio.gz
HROOTFS ?= $(PREBUILT_ROOT)/$(XARCH)/$(CPU)/rootfs.ext2
# Fixup: MP-BIOS bug: 8254 timer not connected to IO-APIC
XKCLI   ?= noapic