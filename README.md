# Welcome to Ocelot
something, something marketing. do we need to do this? if you don't know, prepare to know.

ocelot is the CAN gateway of your dreams.

it allows users to easily retrofit parts from other cars, selectively gateway ECUs at will, filter and convert messages, etc. it's a lot like the gateways in newer cars, but programmable and completely open source.

maybe you want to install an iBooster and control it via RetroPilot or some fork of openpilot that supports ocelot.

maybe you retrofit a new, LKAS-enabled PSCM in your car and want a way to translate messages so the car thinks you still have the old one in.

maybe you just want to gateway your Driving Support Unit and flip a few bits to enable full-speed cruise control.

ocelot has you covered.

## Hardware
ocelot hardware is based on STM32F413, and is fully OSHW. board files, bom, and schematic are located in the `hardware` folder.
The completed hardware is available to purchase on the RetroPilot store. https://shop.retropilot.org/product-category/hardware/ocelot/

## Firmware
ocelot firmware borrows heavily from [panda](https://github.com/commaai/panda), and it should be firmware-compatible with Panda firmware as a black panda. conversely, ocelot firmware should also work on a panda, which is helpful for development.

## Documentation
full documentation and examples are available at the [RetroPilot Wiki](https://wiki.retropilot.org/index/hardware/ocelot):

https://wiki.retropilot.org/index/hardware/ocelot
