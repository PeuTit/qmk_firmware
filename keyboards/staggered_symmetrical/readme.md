# staggered_symmetrical

![staggered_symmetrical](imgur.com image replace me!)

A 64 key keyboard with symmetrical modifiers, split space bar, Hotswap and with Iso layout.
   * This layout starts from a standard ISO 60% layout
   * But split the spacebar in half and add 4 1u keys to each side
   * This allow the user to have a mostly symmetrical layout

* Keyboard Maintainer: [PeuTit](https://github.com/PeuTit)
* Hardware Supported:
- PCB
- Pro Micro 5v/16Mhz
- Hotswap socket
* Hardware Availability: [Staggered-Keyboard](https://github.com/PeuTit/staggered-keyboard)

Compiling (after setting up your build environment):

    qmk compile --keyboard staggered_symmetrical --keymap default

Compiling & Flashing:

    qmk flash --keyboard staggered_symmetrical --keymap default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Physical reset button**: Briefly short the Ground (GND) and the Reset (RST) pads located on the top left of the micro-controller.
