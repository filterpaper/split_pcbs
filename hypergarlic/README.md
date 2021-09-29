# Simplified Hypergarlic

![hypergarlic_custom](hypergarlic_custom.png)

Simplified version of [@davidphilipbarr](https://github.com/davidphilipbarr)'s [hypergarlic](https://github.com/davidphilipbarr/hypergolic/tree/main/hypergarlic) with puck, battery support removed and aligned silkscreens.

## Instructions
To build a Hypergarlic, you need the following:
* 2 [pro-micro](https://www.aliexpress.com/item/32971098005.html) controllers
* 2 [PJ320A](https://www.aliexpress.com/item/1005001928651798.html) audio jack
* 1 male-to-male [TRRS](https://www.aliexpress.com/item/32961128759.html) cable
* 34 [Kailh choc v1](https://www.aliexpress.com/item/4000907409650.html) switches and [keycaps](https://boardsource.xyz/store/5f6ef2d68e3bf05ab838f918)
* Rubber feet or bumbers for the bottom


## QMK Firmware
To build the QMK firmware, compile for Ferris Sweep because both share the same layout:
```
qmk compile -kb ferris/sweep -km default
```
