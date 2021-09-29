# Simplified Architeuthis dux

![architeuthis_dux_custom](architeuthis_dux_custom.png)
![architeuthis_dux_blank](architeuthis_dux_blankv2.png)

Simplified versions of [tapioki](https://github.com/tapioki)'s [Architeuthis dux](https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux) with hotswap socket and puck support removed.

## Instructions
To build an Architeuthis dux, you need the following:
* 2 pro-micro controllers
* 2 PJ320A audio jack
* 1 male-to-male TRRS cable
* 34 Kailh choc v1 switches and keycaps
* Rubber feet or bumbers for the bottom

Note: Architeuthis dux is a double sided PCB so controllers face down on the left and face up on the right.

## QMK Firmware
To build the QMK firmware, run:
```
qmk compile -kb a_dux -km default
```
