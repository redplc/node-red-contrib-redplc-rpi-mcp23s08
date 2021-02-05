# node-red-contrib-redplc-rpi-mcp23s08

redPlc module node for MCP23008 8bit I/O Expander.<br>

## Install

[redPlc use this module node. Install redPlc.](https://www.npmjs.com/package/node-red-contrib-redplc)

[If you use this node for other nodes install this.](https://www.npmjs.com/package/node-red-contrib-redplc-module)

Install with Node-Red Palette Manager or npm command:
```
cd ~/.node-red
npm install node-red-contrib-redplc-rpi-mcp23s08
```
## Usage
Wire this node to first output of redPlc cpu node.<br>
Global variable I are updated with digital inputs.<br>
Global variable Q sets digital output.<br>
This node works only on Raspberry Pi with Raspberry Pi OS.<br>
Enable SPI with raspi-config.

### Digital Input (Variable I):
### Digital Output (Variable Q):

|Pin|Bit|
|:--|:-:|
|GP0|0|
|GP1|1|
|GP2|2|
|GP3|3|
|GP4|4|
|GP5|5|
|GP6|6|
|GP7|7|

## Donate
If you like my work please support it with donate:

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ZDRCZBQFWV3A6)
