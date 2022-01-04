# WTL62-QMK

#### Use guide
clone to qmk_firmware/keyboards
#### Compiling
`qmk compile -kb WTL62 -km keymap`
- replace keymap with keymap you would like to compile. This repo contains only default keymap
#### Flashing default .hex file
[QMK Toolbox](https://github.com/qmk/qmk_toolbox) is the easiest way to do this. Short pins `gnd` and `rst` on yours MCU to reset
