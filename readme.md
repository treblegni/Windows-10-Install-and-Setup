##Guide for Windows 10 fresh install and setup

This guide is meant for learning purposes and must not be applied in professional environments without proper understanding of the methods covered. There are constant changes to these types of guides, so it is best to research current trends. Use this guide as a basis.

Table of Contents:
- [Windows 10 Fresh Install](###windows-10-fresh-install)
	- [Creating A  Bootable Flash Drive](#boot-drive)
	- [BIOS Configuration](#bios)
		- [Set UEFI Interface](#uefi)
		- [Disabling Secure Boot](#secure-boot)
	- [Booting From Flash Drive](#boot-from)
		- [Configure Boot Priority](#priority)
	- [Windows 10 Installation](####Windows-10-Installation)
		- [Installation Wizard](#wizard)
- [Windows 10 Setup](#setup)

---

###Windows 10 Fresh Install

A fresh install means that we will be installing a fresh copy of Windows 10 on to the computer. Any and all data on the drive will be wiped. Please backup up all important data prior to reaching to doing a fresh install.

####Creating A Bootable Flash Drive

The first step is to create a bootable drive.

	Note: Step still in the works.

####BIOS Configuration

Our bootable drive will be created with the UEFI interface. This is a new type of interface that allows interaction of Software between the Operating System and Firmware. We need to configure this in the computers BIOS. The BIOS must be setup to support UEFI. We also need to disable Secure Boot to perform a fresh install.

#####Reaching the BIOS menu
- First, shut off your computer.
- Turn on the computer and press on the "F2" key on your keyboard to reach the BIOS menu.

![](https://philipyip.files.wordpress.com/2016/07/dell-business-uefi-bios.png?w=920&h=522)

	Note: This menu will look uniquely different on other brands. This method illustrates the BIOS found on Dell computers.

#####Set UEFI Interface
- Click on "General" settings and then on "Boot Sequence"
- Make sure "UEFI" is ticked and not "Legacy", then click on "Apply"

![](https://static.spiceworks.com/shared/post/0021/8341/UEFI_BIOS_Boot_Select.png)

- Next click on "Secure Boot" settings and then "Secure Boot Enable" and make sure that "Disabled" is ticked under the "Secure Boot Enable" option.

![](https://kbimg.dell.com/library/KB/DELL_ORGANIZATIONAL_GROUPS/DELL_GLOBAL/Content%20Team/UEFI_BIOS_SecureBoot_Disabled.png)

- Click on "Apply", then "Exit" to reboot your computer.

	Note: Before your click on "Exit", look at the next step to prepare.

####Booting From Flash Drive

We will be installing the Windows 10 OS with a bootable drive. It is essential that you check the previous steps to guarantee and successful installation.

#####Configure Boot Priority
- To reach the boot menu, press the key "F12" before the computer boots. Usually a a logo of computer's brand will appear before the computer boots. Press "F12" at least once to initiate the boot menu.
- You should then reach boot menu. Make sure the Boot is set to UEFI and Secure Boot is off.
- If the above is achieved, then use your arrow keys on the keyboard to navigate to "UEFI: <YOURFLASHDRIVESNAME>". Press enter start the boot.

![](https://i.imgur.com/0h7t5tZ.png)

- The computer should lead to Windows 10 install wizard in a couple minutes

####Windows 10 Installation

After setting up the BIOS for the PC, the next step is to install the OS (operating system). This is achieved by doing the previous step to boot from a bootable flash drive that has the Windows 10 image.

#####Configuring The Installation
- You will be prompted with the Windows Setup window where you need to select the language, time, and keyboard layout for your computer.

![](https://www.itechguides.com/wp-content/uploads/2019/04/Download-Windows-10-10-select-language-timea-currency-and-keyboard-to-install-.png)

