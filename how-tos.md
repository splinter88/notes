# HowTos

## Create bootable Windows USB using Ubuntu

1. Install gparted.
2. Erase and partition the USB
  * Set partition type to GPT
  * Format the partition to FAT32 (since UEFI bootloader supports FAT32 - learn more about [partition formats](http://www.howtogeek.com/235596/whats-the-difference-between-fat32-exfat-and-ntfs/))
3. Copy Windows files from a mounted ISO image to the USB.
4. Use gparted to set the 'boot' flag on the partition.
