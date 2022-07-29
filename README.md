# AZERTY patch for **Bad USB** module

This patch allows you to use the **Bad USB** module on computers configured to use the AZERTY layout instead of the QWERTY layout.

### Installation
1. Replace `firmware/targets/furi_hal_usb_hid.h` with the patched version : [furi_hal_usb_hid.h](furi_hal_usb_hid.h)
2. Compile the firmawre : `sudo docker-compose up -d && sudo docker-compose exec dev ./fbt`
3. Flash the firmware : In the qFlipper companion app, choose `Install from file` and use `/dist/f7-D/flipper-z-f7-full-local.dfu`

### Contributers

[p-h-0-x](https://github.com/p-h-0-x)
