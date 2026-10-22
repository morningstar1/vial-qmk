# pttbutton

![pttbutton](https://github.com/morningstar1/PTTButton/blob/main/image/PTTButton.png?raw=true)

A simple one-button keyboard with a USB hub. Its primary purpose is to serve as a Push-to-Talk (PTT) button.

* Keyboard Maintainer: Sebastian Morgenstern
* Hardware Supported: [PTTButton V1.0](https://github.com/morningstar1/PTTButton)
* Hardware Availability: Please contact me at <sebastian.morgenstern@gmail.com>.

To build this keyboard (after setting up your build environment):

    make morningstar1/pttbutton:default

To flash this keyboard:

    make morningstar1/pttbutton:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter bootloader mode using the physical reset button:

Briefly press the small button on the PCB.