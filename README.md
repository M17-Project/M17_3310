# M17_3310
Mainboard replacement for the Nokia 3310/3330.

> [!CAUTION]
> The board's thickness is 1.0mm. Anything thicker **will not** fit.

## Original mainboard photos
Both photos in the `misc` directory are cropped, so that if you scale them for 108mm height, you should be able to make direct measurements using GIMP or other image editing software.

## SA868S UHF module firmware
The RF module should be flashed with [OpenRTX](https://github.com/OpenRTX/sa8x8-fw). The instructions on how to do that are in the readme, see the [*Firmware Flashing*](https://github.com/OpenRTX/sa8x8-fw?tab=readme-ov-file#firmware-flashing) section for details. The RF module can be flashed before, or after soldering it in place.

> [!NOTE]
> The device will appear frozen if the firmware running on the RF module is not OpenRTX.

## Device firmware
See the example firmware [here](https://github.com/M17-Project/M17_3310-fw).

### Flashing over USB
1. Plug in the USB cable.
2. Press and hold the *OK* button (large horizontal one with a blue bar, just below the display).
3. Press the power button at the top of the device.
4. Release the *OK* button.

The device should enter USB DFU mode and should be recognized by CubeProgrammer.
