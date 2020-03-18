## Guide for Windows 10 fresh install and setup

This guide is meant for learning purposes and must not be applied in professional environments without proper understanding of the methods covered. There are constant changes to these types of guides, so it is best to research current trends. Use this guide as a basis.

Table of Contents:
- [Windows 10 Fresh Install](#fresh-install)
	- [Creating A  Bootable Flash Drive](#boot-drive)
	- [BIOS Configuration](#bios)
		- [Set UEFI Interface](#uefi)
		- [Disabling Secure Boot](#secure-boot)
	- [Booting From Flash Drive](#boot-from)
- [Windows 10 Setup](#setup)

---

### Windows 10 Fresh Install

A fresh install means that we will be installing a fresh copy of Windows 10 on to the computer. Any and all data on the drive will be wiped. Please backup up all important data prior to reaching to doing a fresh install.

#### Creating A Bootable Flash Drive

The first step is to create a bootable drive.

Note: Step still in the works.

#### BIOS Configuration

Our bootable drive will be created with the UEFI interface. This is a new type of interface that allows interaction of Software between the Operating System and Firmware. We need to configure this in the computers BIOS. The BIOS must be setup to support UEFI. We also need to disable Secure Boot to perform a fresh install.

##### Reaching the BIOS menu
- First, shut off your computer.
- Turn on the computer and press on the "F2" key on your keyboard to reach the BIOS menu.

![](https://philipyip.files.wordpress.com/2016/07/dell-business-uefi-bios.png?w=920&h=522)

	Note: This menu will look uniquely different on other brands. This method illustrates the BIOS found on Dell computers.

##### Set UEFI Interface
- Click on "General" settings and then on "Boot Sequence"
- Make sure "UEFI" is ticked and not "Legacy", then click on "Apply"

![](https://static.spiceworks.com/shared/post/0021/8341/UEFI_BIOS_Boot_Select.png)

- Next click on "Secure Boot" settings and then "Secure Boot Enable" and make sure that "Disabled" is ticked under the "Secure Boot Enable" option.

![](https://kbimg.dell.com/library/KB/DELL_ORGANIZATIONAL_GROUPS/DELL_GLOBAL/Content%20Team/UEFI_BIOS_SecureBoot_Disabled.png)

- Click on "Apply", then "Exit" to reboot your computer.

