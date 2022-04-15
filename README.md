# 0xcb-TutelPad
## An 8-key macropad with a 128x64 pixel OLED display

Licence | OSHWA
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-TutelPad/blob/main/LICENSE.svg) | [![](https://github.com/0xCB-dev/0xcb-TutelPad/blob/main/PCB/rev1.0/OSHWA.svg)](https://certification.oshwa.org/.html)

### QMK

[keyboards/0xcb/tutelpad/](https://github.com/qmk/qmk_firmware/tree/master/keyboards/0xcb/tutelpad)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* Press switch 1 while plugging in to go into dfu mode (or the reset button)
* `make 0xcb/tutelpad:via:flash`

### Assembly:

You can use the [humanpnp](https://files.0xcb.dev/0xCB-TutelPad/humanpnp.html) to easily place components.

### PCB:
KiCad 6 stable release - using these [libs](https://github.com/0xCB-dev/0xcb-libs)

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev1.0/top.png)  |  ![](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev1.0/bottom.png)

### CAD files:

[DXF](https://github.com/0xCB-dev/0xcb-1337/tree/main/rev4.0/1337-freecad.FCStd)

[SolidWorks](https://github.com/0xCB-dev/0xcb-1337/tree/main/rev4.0/1337-v4.0.step)

#### BOM:
 References                        | Value          | Quantity | Part Nb.            
-----------------------------------|----------------|----------|---------------------
 SW1                               | SPST RA        | 1        | C115343             
 RGB4,RGB3,RGB2,RGB1               | WS2812B        | 4        | C114586             
 OL1                               | SSD1306-128x64 | 1        | amazon              
