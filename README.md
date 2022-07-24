# AZERTY patch for Bad USB module

With this patch, you can use the **Bad USB module** on computers configured to use the AZERTY layout

I based myself on this file [https://github.com/Log-s/flipperzero-contributions](this) which I adapted to the new firmware.

I will try to update it regularly if the firmware evolves

### Installation
1. First replace `\firmware\targets\furi_hal_include\furi_hal_usb_hid.h` with the patched version: [furi_hal_usb_hid.h](furi_hal_usb_hid.h)
2. To compile the firmware, you can use the following tutorial: https://github.com/Eng1n33r/flipperzero-firmware/blob/dev/documentation/HowToBuild.md
3. To flash the firmware : In the qFlipper companion app, choose Install from file then use `\dist\f7-C\flipper-z-f7-full-local.dfu`
