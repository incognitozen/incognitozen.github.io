---
title: UNetbootin
draft: false 
website: https://unetbootin.github.io
classification: ['Bootable USB Creator']
platform: ['Linux', 'Windows']
keywords: ['aio_boot', 'deepin_boot_maker', 'drivedroid', 'easybcd', 'etcher', 'linuxlive_usb_creator', 'mac_linux_usb_loader', 'multibootusb', 'multisystem', 'rmprepusb', 'rufus', 'sardu', 'ultimate_boot_cd', 'universal_usb_installer', 'winsetupfromusb', 'wintoflash', 'xboot', 'yumi', 'dd']
image: 2020/04/UNetbootin.png
---
UNetbootin is a utility for creating live bootable USB drives. The name of the software is short for Universal Netboot Installer, and its most prevalent use has been to create bootable versions of Linux distributions on a USB drive.

UNetbootin doesn't use distribution-specific rules for making your live USB drive, so most Linux ISO files should load correctly using this option. However, not all distributions support booting from USB, and some others require extra boot options or other modifications before they can boot from USB drives, so these ISO files will not work as-is. Also, ISO files for non-Linux operating systems have a different boot mechanism, so don't expect them to work either.
<h3>Requirements</h3>
1 GB or larger USB drive, formatted as FAT32 (most USB drives come formatted as FAT32 by default, but if you need to format it, on Windows, go to My Computer-&gt;right click your USB drive-&gt;format, or on Linux, use GParted or another partition manager)

Supported operating systems: <em>Windows</em> 2000 and above OR a modern <em>Linux</em> distribution. UNetbootin can also be run from Mac OS X, but note that only PCs (not Macs) can boot the resulting live USB drives.

On <em>Windows</em> XP, you must be logged on as an administrator; on <em>Windows</em> Vista and above, you will be prompted for permissions via UAC.

Additional dependencies (<em>Linux Only</em>): You will need the packages <em>syslinux</em> and <em>p7zip-full</em> installed (no dependencies on Windows)
<div class="column">

</div>