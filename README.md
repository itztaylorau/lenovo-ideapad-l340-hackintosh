**Updated: I purchused a Macbook Pro 16 and didn't use L340 anymore. This repository will not be maintain.**

# Lenovo Ideapad L340 Gaming Hackintosh

![Cover](/docs/cover.png)

## System Specification

IdeaPad L340-15IRH Gaming specification:

| Type | Name | Note |
| --- | --- | --- |
| CPU | Intel Core i5 9300H | |
| Graphics | Intel UHD Graphics 630 | Disabled GTX 1050 |
| Display | 15.6in FullHD | |
| RAM | 8GB DDR4 | Upgradable to 16GB DDR4 |
| Wifi| BCM94352Z - DW1560 | Default Intel Wifi does't work. |
| NVME SSD| Western Digital Black SN750 NVMe SSD 500GB | No SSD default|
| SATA Disk | Seagate Moments Thin 500GB | |
| USB | 2 USB 3.1 + 1 USB 3.1 Type C | |
| Trackpad | Synaptics SYNA2B52 |
| Audio | Realtek ALC 257 |
| BIOS version| BGCN28WW - BGCN29WW |
| OSX version| Monterey 12.0.1 (21A559) |

## Not working?

- GTX 1050 (Disabled)
- HDMI Port (it was connected with GTX 1050)

## To do
1. Separate Trackpad patch from DSDT.aml for OpenCore.
2. Further check regaring other files and folders

## Installation notes - OpenCore

- Copy kexts in ```EFI``` folders to your EFI partiton.

- If your hackintosh crash at booting, remove __DSDT.aml__ and try again.

## Credits
- Copyrights of khanhtran-cse /lenovo-ideapad-l340-hackintosh
- Apple for macOS

## Logs

### JAN 2022

- Updated  khanhtran-cse /lenovo-ideapad-l340-hackintosh to Monterey 12.0.1 (21A559) capable
