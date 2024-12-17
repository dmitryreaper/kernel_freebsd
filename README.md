# kernel_freebsd

this core was built specifically for the thinkpad x1 carbon gen 6 laptop
What has been removed from the core:

- Network Filesystem Client
- Network Filesystem Server
- Network Lock Manager
- NFS usable as /, requires NFSCL
- MSDOS Filesystem
- ISO 9660 Filesystem
- RAID controllers
- RAID controllers interfaced to the SCSI subsystem
- support MMC/SD
- VirtIO support
- Linux KVM paravirtualization support
- Nvidia/Mellanox Connect-X 4 and later, Ethernet only
- HyperV drivers and enhancement support
- Delay (in ms) before probing SCSI
- ktrace(1) support
- stack(9) support
- Ensure frames are compiled in
- Kernel DTrace hooks
- Enable kernel debugger support.
- Print a stack trace for a panic.
- Kernel Sanitizers
- Generic kernel coverage. Used by KCOV
- Kernel Coverage Sanitizer
- Kernel Undefined Behavior Sanitizer
- Kernel Concurrency Sanitizer
- Support for encrypted kernel dumps
- gzip-compressed kernel and user dumps
- zstd-compressed kernel and user dumps
- debugnet networking
- netdump(4) client support
- netgdb(4) client support
- Floppy drives
- SCSI Controllers (all)
- RAID controllers (all)
- CardBus bridge support
- Serial (COM) ports
- Parallel port (all)

## Wireless NIC cards
	
Since FreeBSD automatically installs the iwm core module package for 8265 / 8275 cards during installation, there is no need for other card supports built into the core.

Support has been removed:

- Broadcom BCM430x/BCM431x wireless NICs.
- Broadcom BCM43xx wireless NICs.
- Intel 2100 wireless NICs.
- Intel 4965/1000/5000/6000 wireless NICs.
- Marvell Libertas wireless NICs.
- Marvell 88W8363 802.11n wireless NICs.
- Ralink Technology RT2500 wireless NICs.
- Intel 3945ABG wireless NICs.

with PCI Ethernet, the same thing is the iwm module already includes Ethernet support

Support has been removed:

- Attansic/Atheros L2 FastEthernet
- Attansic/Atheros L1 Gigabit Ethernet
- Atheros AR8131/AR8132 Ethernet
- Atheros AR8121/AR8113/AR8114 Ethernet
- Broadcom BCM5706/BCM5708 Gigabit Ethernet
- Broadcom BCM440x 10/100 Ethernet
- Broadcom BCM570xx Gigabit Ethernet
- Sun Cassini/Cassini+ and NS DP83065 Saturn
- DEC/Intel 21143 and various workalikes
- Agere ET1310 10/100/Gigabit Ethernet
- Intel EtherExpress PRO/100B (82557, 82558)
- Sun GEM/Sun ERI/Apple GMAC
- JMicron JMC250 Gigabit/JMC260 Fast Ethernet
- Level 1 LXT1001 gigabit Ethernet
- Marvell/SysKonnect Yukon II Gigabit Ethernet
- nVidia nForce MCP on-board Ethernet
- NatSemi DP83820 gigabit Ethernet
- RealTek 8139C+/8169/8169S/8110S
- RealTek 8129/8139
- Silicon Integrated Systems SiS190/191
- Silicon Integrated Systems SiS 900/SiS 7016
- SysKonnect SK-984x & SK-982x gigabit Ethernet
- Sundance ST201 (D-Link DFE-550TX)
- Sundance/Tamarack TC9021 gigabit Ethernet
- VIA VT612x gigabit Ethernet
- VIA Rhine, Rhine II
- 3Com 3c90x ('Boomerang', 'Cyclone')



