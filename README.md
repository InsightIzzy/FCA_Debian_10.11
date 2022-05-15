# FCA_Images
this repo holds all Linux images for all FCA hw versions

## repo contains
- boot dir: holds the file for boot partition.
- fs dir: holds filesystem .tar file for the file-system partition.

### boot dir
- BOOT.BIN.
- image.ub.
- system.dtb.

### fs dir
- debian-10.11-minimal-armhf-2021-11-02.tar.
this file is zipped due to git FILE_MAX_SIZE

## How to use
You will need an SD-Card with 8GB+
- Create FAT32 partition (512MB) call BOOT and make it bootable.
- Create an ext-4 partition (rest of the SD size) call rootfs.
- copy the file form the boot directory on this repository to BOOT folder.
- extract the .tar file from fs directory in this repository to the rootfs.

## Note
this will boot a clean debian 10.11 version on your device,
which mean you will need to install your desire packages (python etc')

### Authors
Israel Yesha'ayahu (israely@insightec.com)

### copyright
Copyright © 2002 by InSightec
