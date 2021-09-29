# Simplified Hypergarlic

![hypergarlic_custom](hypergarlic_custom.png)

Simplified version of [@davidphilipbarr](https://github.com/davidphilipbarr)'s [hypergarlic](https://github.com/davidphilipbarr/hypergolic/tree/main/hypergarlic) with puck, battery support removed and aligned silkscreens.

## Instructions
To build an Architeuthis dux, you need the following:
* 2 pro-micro controllers
* 2 PJ320A audio jack
* 1 male-to-male TRRS cable
* 34 Kailh choc v1 switches and keycaps
* Rubber feet or bumbers for the bottom

## QMK Firmware
To build the QMK firmware, compile for Ferris Sweep because both share the same layout:
```
qmk compile -kb ferris/sweep -km default
```
