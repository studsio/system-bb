# Changelog

#### Version 1.3 (working)
* Convert system name to `bb` to reflect broader BeagleBone support
* Firmware updates verify that target. If the target != `bb` update fails
* Added meta-misc and meta-vcs-identifier to the `fwup.conf`
* Nerves toolchain v0.12.1
* Buildroot 2017.11
* u-boot 2017.09
* Linux 4.4.91 w/ RCN's patches
* Add global patch directory
* nbtty 0.3.0
* Support for pocketbeagle
* Clear out the wl18xx MAC address field to use TI default MAC address
* Support for reverting firmware
* Enable scaling processor frequency based on workload

#### Version 1.2 (29-Nov-2017)
- Remove Erlang/erlinit/Exilir depends

#### Version 1.1 (15-Aug-2017)
- Fork from nerves_system_bbb
- Buildroot 2017.05
- Bump Linux kernel to 4.4.60
- Bump toolchain to use gcc 5.3 (previously using gcc 4.9.3)
- Bump fwup to 0.15.3
- Initial support for BBG Wireless
- The application data partition is now `ext4`
- The boot partition is managed in an A/B style to support more robust firmware updates.
- The Linux kernel is no longer compiled for SMP. All Beaglebone variants are single processor.

#### Version 1.0
Duplicate nerves-system-bbb images
