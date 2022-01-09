#
# Copyright (C) 2006-2020 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

PKG_NAME:=firmware-utils
PKG_RELEASE:=1

PKG_SOURCE_PROTO:=git
PKG_SOURCE_URL=https://github.com/0x4A6F/firmware-utils.git
PKG_SOURCE_DATE:=2022-01-16
PKG_SOURCE_VERSION:=c098d55bb8611d6b95e82a4a45ea18e7bfa49915
PKG_MIRROR_HASH:=91f1bac08af2d856e93e651dc7c1ce6745f0b32b6fe4fb1917660494d7518057

include $(INCLUDE_DIR)/host-build.mk
include $(INCLUDE_DIR)/cmake.mk

$(eval $(call HostBuild))
