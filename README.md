RPi
===

Reference files for "An Advanced Streaming Internet Radio Player with Raspberry Pi," by Jeremy Gilreath and Chafic BouSaba

========== /etc/rc.local

This script is executed at the end of each multiuser runlevel. Adding commands to the bottom of this script is an easy way to perform necessary tasks like starting special services or initialize devices without writing complex initialization scripts.

========== /etc/network/interfaces

The network interface configuration file.

========== /etc/lirc/lircrc

Combines the IR remote buttons with lirc application capabilities.

========== /etc/lirc/lircd.conf

LIRC driver to convert the IR pulse data into key symbols.

========== /etc/lirc/hardware.conf

Arguments, modules, drivers, and configuration for launching lirc.

========== /etc/modules

Contains the names of kernel modules that are to be loaded at boot time, one per line. Arguments can be given in the same line as the module name.

========== /etc/inittab

When you boot the system or change run levels with the init or shutdown command, the init daemon starts processes by reading information from this file, which defines three important items for the init process:

1) The system's default run level

2) What processes to start, monitor, and restart if they terminate

3) What actions to take when the system enters a new run level

Each entry in the /etc/inittab file has the following fields:

id:rstate:action:process
