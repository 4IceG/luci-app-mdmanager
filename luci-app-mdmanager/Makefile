#
# Copyright 2025 Rafał Wabik - IceG - From eko.one.pl forum
#
# MIT License.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-mdmanager
PKG_VERSION:=1.0.5
PKG_RELEASE:=20251116
LUCI_TITLE:=LuCI JS Mini Disk Manager
MAINTAINER:=Rafał Wabik <4Rafal@gmail.com>
LUCI_DESCRIPTION:=Interface for managing disk partitions and filesystems in OpenWrt.
LUCI_DEPENDS:=+luci-base +block-mount +fdisk +parted +lsblk +e2fsprogs +ntfs-3g +dosfstools +swap-utils
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature

