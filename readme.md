# Right sided Artsey paintbrush QMK FW for Sparkfun Pro Micro RP2040 MCU

* Keyboard Maintainer: [eggg-uk](https://github.com/eggg-uk)
* Hardware Supported: "Sparkfun Pro Micro RP2040" MCU

# build environment setup

pip3 install --user qmk

qmk setup

qmk doctor

qmk new-keyboard

qmk new-keymap right

qmk config user.keyboard=paintbrush


## Make example for this keyboard (after setting up your build environment):

    qmk compile -kb paintbrush -keymap right

## Flashing example for this keyboard:

    qmk flash -kb paintbrush -keymap right

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in the documented way for the first time flash
after flashing QMK for the first time you can double press reset to enter it more easily
