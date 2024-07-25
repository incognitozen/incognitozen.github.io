---
date: 2024-25-07
draft: false
params:
  author: Dave Smith
title: Speed Up Your Linux
weight: 10
---

Every time a file is read from your Linux ext3 partition it writes back a attribute to the file detailing the last access time. There are very few programs that actually use this to operate and it slows everything down.

Disabling atime and diratime on your Linux ext3 file systems can improve disk performance up to 40%! WARNING: If you are using programs such as tmpwatch, mutt, or mail-notify this configuration change could cause those programs that make specific use of atime not to work.

-   Start a terminal.
-   Switch to root using the "su -" command.
-   Backup your fstab -- "cp /etc/fstab /etc/fstab.old".
-   Open your /etc/fstab in the editor of your choice (nano, kate or gedit recommended). This can be done by issuing the command "nano /etc/fstab", "kate /etc/fstab", or "gedit /etc/fstab".
-   Locate the partitions that contain your / and /home file systems, as well as any other file system you want to optimize. Examples include /dev/hda2 and /dev/hda3, or /dev/sda2 and /dev/sda3.
-   In the fourth section (just before the two numbers at the end of the line) you will see the options section of the fstab.
-   Enter ",noatime,nodiratime" after the existing options for each partition you wish to optimize.
-   Save the fstab file.
-   Reboot.

Enjoy your newly optimized Linux ext3 file system.