# flipperzero-contributions
This repo will contain my contributions to the Flipperzero project (it's a bit empty right now).

The open-source firmware: https://github.com/flipperdevices/flipperzero-firmware

## AZERTY patch for **Bad USB** module

This patch allows you to use the **Bad USB** module on computers configured to use the AZERTY layout instead of the QWERTY layout.

### Installation
1. Replace `firmware/targets/furi_hal_usb_hid.h` with the patched version : TODO
2. Compile the firmawre
3. Flash the firmware
