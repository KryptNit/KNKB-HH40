
A handwired RP2040 Zero - 40% keyboard case featuring a classic HHKB-inspired layout with corner blockers. Designed around a gasket bean mounting system to deliver a cushioned typing feel.

Features:

Layout: 40% HHKB style
Mounting: Gasket bean mount for controlled flex
Keymap: Customizable keymap - QMK/Vial/VIA

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
|[3D Printed Gasket beans (TPU)](https://makerworld.com/en/models/1412694-minimal-macropad#profileId-1466694)|4|
|Bolt M2.5x16 |4|
|Heat set Insert M2.5x2 |4|
|Bolt M2x5 (for RP2040 Holder) |2|

Assembly Steps:

<img width="2880" height="2160" alt="image3" src="https://github.com/user-attachments/assets/ea0a0c22-7935-42dc-9d1a-4380ad23d048" />
<img width="2880" height="2160" alt="image5" src="https://github.com/user-attachments/assets/83fe4ca3-f1e0-44f8-afec-7341d5c7ab08" />
<img width="2880" height="2160" alt="image7" src="https://github.com/user-attachments/assets/3982a410-a05a-4c10-9a56-3beceeb29196" />
<img width="2880" height="2160" alt="image6" src="https://github.com/user-attachments/assets/c44050b6-45f4-46d3-9e35-4ee787962318" />
<img width="2880" height="2160" alt="image8" src="https://github.com/user-attachments/assets/66f421f0-406c-4336-85f3-bcf20357c6f2" />
<img width="2880" height="2160" alt="image9" src="https://github.com/user-attachments/assets/769a651b-b5f6-4e00-a65d-d78e58187dd9" />
<img width="2880" height="2160" alt="image10" src="https://github.com/user-attachments/assets/ad957549-5355-4326-b131-d471ecdaa3a1" />

Install Heat set Inserted to the Top Case 4 corners
<img width="2880" height="2160" alt="image11" src="https://github.com/user-attachments/assets/7894b485-1b5d-434e-8b44-65eeeab57c0c" />




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
