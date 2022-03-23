# Little Foot
<br>
<img src="https://github.com/sethpoly/little-foot-keyboard/raw/main/img/little_foot_pcb_1.0.12.PNG" width=100% height=100%>
<br>

*Command to flash:*
`avrdude.exe -p atmega32u4 -c avr109 -U flash:w:"C:/Users/email/repos/qmk_firmware/keyboards/carpal26/carpal26_default.hex":i -P COM4`

*A short description of the keyboard/project*
*TODO*
* Keyboard Maintainer: [sethpoly](https://github.com/sethpoly)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make carpal26:default

Flashing example for this keyboard:

    make carpal26:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `RESET` if it is available
