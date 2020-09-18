include $(TOPDIR)/rules.mk

ARCH:=aarch64
BOARD:=ipq807x
BOARDNAME:=Qualcomm Atheros IPQ807x
FEATURES:=squashfs ramdisk source-only
KERNELNAME:=Image dtbs
CPU_TYPE:=cortex-a53

KERNEL_PATCHVER:=5.4

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += \
	kmod-ath11k \
	ath11k-firmware-ipq807x \
	kmod-qca-nss-crypto \
	kmod-qca-nss-dp \
	kmod-qca-nss-drv \
	kmod-qca-ssdk-nohnat \
	wpad-openssl

$(eval $(call BuildTarget))
