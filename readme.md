
A handwired RP2040 Zero - 40% keyboard case featuring a classic HHKB-inspired layout with corner blockers. Designed around a gasket bean mounting system to deliver a cushioned typing feel.

Features:

Layout: 40% HHKB style

Mounting: Gasket bean mount for controlled flex

BOM
|Items|Qty|
|:---|:---:|
|Mx Switches |40|
|Diode 1N4148 |40|
|Plate Mount Stabilizer |2|
|RP2040 Zero |1|
|Copper Wire | |
|Heat Shrink Tube | |
|AWG30 Wire | |
|[3D Printed Case and Swich Plate](https://makerworld.com/en/models/1412694-minimal-macropad#profileId-1466694)|1 Set|
|Bolt M2.5x16 |4|
|Heat set Insert M2.5x2 |4|
|Bolt M2x5 (for RP2040 Holder) |2|


* Keyboard Maintainer: [KryptNit](https://github.com/KryptNit)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make hh40:default

Flashing example for this keyboard:

    make hh40:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
