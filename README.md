# node-red-contrib-redplc-rpi-mcp23s08

Node-Red node for mcp23s08 8bit I/O Expander.<br>

## Node Features
- 8 x Digital Inputs or Digital Outputs
- Add Pullup Resistor to Digital Inputs
- Four selectable Spi channels
- Four selectable Device Addresses

## Install

For using with Ladder-Logic install
[redPlc](https://www.npmjs.com/package/node-red-contrib-redplc) nodes

For using with other nodes, install
[module](https://www.npmjs.com/package/node-red-contrib-redplc-module) nodes

Install with Node-Red Palette Manager or npm command:
```
cd ~/.node-red
npm install node-red-contrib-redplc-rpi-mcp23s08
```
## Usage
This node reads/writes from/to Node-Red global variables<br>
Update is triggered by redPlc cpu node or module-update node<br>
This node works only on Raspberry Pi with Raspberry Pi OS<br>
Enable SPI with raspi-config<br>
Consult datasheet for absolute maximum ratings<br>

### Digital Input (Variable I):
### Digital Output (Variable Q):

|Pin|Bit|
|---|---|
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
