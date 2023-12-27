# wtl62

#### Hardware disclaimer
The folder structure is fucked up and probably wont be fixed as i see no reason for this.
Top case part (plate) is located in the bottom case part folder, and this one is located in the general pcb folder. Yeah.
There's also Willing To Live Better 62 inside, but this one proly wont' see a light of day as there prolly aint no interest in this design. Have fun.


#### firmware use guide
clone wtl62 folder to qmk_firmware/keyboards
#### Compiling
`qmk compile -kb WTL62 -km keymap`
- replace keymap with keymap you would like to compile. This repo contains only default keymap
#### Flashing default .hex file
[QMK Toolbox](https://github.com/qmk/qmk_toolbox) is the easiest way to do this. Short pins `gnd` and `rst` on yours MCU to reset
#### Using Vial
1. Flash `wtl62_via.hex` file to the keyboard
2. Open Vial
3. Go to File>Sideload VIA JSON...
4. Select `via.json` file
5. Voila! Now you can configure wtl62 using Vial
