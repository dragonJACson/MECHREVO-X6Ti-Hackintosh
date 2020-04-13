# MECHREVO-X6Ti-Hackintosh

Hackintosh Configurations of Mechrevo X6Ti(-m)

## Notice

```cpp
#include <std_disclaimer.h>
/*
 * Your warranty is now void.
 * You are working on your own device, and I am not responsible for any
 * bricked devices.
 */
```

## Device specifications

| Device       | Mechrevo X6Ti-m                                     |
| -----------: | :---------------------------------------------- |
| Chipset | Intel HM170 |
| CPU          | Intel i5-6300HQ  |
| GPU | Nvidia Geforce GTX 965m & HD Graphics 530                             |
| Memory       | 8 GB 2133 MHz DDR4 from Samsung (+ 8 GiB 2400 MHz DDR4 from Team)         |
| HDD      | Seagate ST1000LM024 HN-M101MBB                           |
| SSD       | LiteOn CV1-CB64 (Replaced with WD SN550 1TiB by myself)                                   |
| Audio Card      | Realtek ALC269                   |
| Wireless Network Adapter | Intel AC-3165 (Replaced with AC-9260 by myself)                         |
| Ethernet Network Adapter | Realtek RTL8168 / RTL8111 |
| Display Panel      | LG LP156WF6-SPB1            |
| Battery | 10.8 V * 4400 mAh = 47.52 Wh |
| Dimensions | 382 * 266 * 32-35 mm |
| Weight | 2.7 KG |
| Shipped OS version | Windows 10 Home x64                                             |
| I/O Ports | 2 * USB 3.0 + 2 * USB 2.0 + 1 * USB 3.1 Type-C (Don't support TB and Video output) + SD Slot + Audio-in + Audio-out + HDMI + RJ45 |
| Internal Slots | 1 * m.2 2230 M key for Wireless Network Adapter + 2 * m.2 2280 (SATA / PCIe) + 2 * RAM Slots + 2.5 Inch SATA (9.5 mm) |

## Status
The Clover Configuration is not maintained anymore.

The OpenCore Configuration is only tested on 10.14.6.

I don't use patched DSDT file but a lot of SSDT hotpatches, which should deal with different BIOS versions and different hardwares.

Don't forget to fill PlatformInfo with your own data.

On my computer, kernel panic will happen on Catalina for some reason, while I can't solve it.

### What is working
- Memory
- USB 2.0 + USB 3.0
- Ethernet
- Display
- Audio
- SSD
- Fn shortcuts for brightness and audio volume

### What is not working

- SD Slot
- HWP CPU Power management
- USB Type-C Port
- Touchpad and numpad
- Stock Wireless Network Adapter
- Nvidia Graphics Card


