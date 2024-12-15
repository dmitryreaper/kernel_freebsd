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
- Nvidia/Mellanox Connect-X 4 and later, Ethernet only (in testing)
- HyperV drivers and enhancement support (in testing)
