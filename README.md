![Render using JLCPCB's PCBA visualiser](/dongle_image_jlcpcb.png?raw=true "Render using JLCPCB's PCBA visualiser because KiCAD doesn't have the MOLEX USB connector 3d model")

This is an attempt to make as miniature of a dongle for ZMK as is realistically possible. PCB size: 20.66mmx11.3mm

By realistically, I mean to not be completely unaffordable to produce. 
It could be made smaller through the use of components on both sides and via-in-pad, but this would raise the cost by a large degree. Likewise for reducing the width of traces even further - theoretically sound and wouldn't have any issues with the current levels we are dealing with, but financially unviable.

Despite my best efforts, it turns out to be financially unviable for PCBA -- in large enough quantities it would be fine, but thanks to FCC/CE certification the amount of orders needed would be unrealistic for something like this.

However, it should be perfectly fine for someone who has a hot plate and happens to be ordering parts from a site such as digikey/mouser already. If someone has a reflow oven and wants me to design a version that has components on both sides, let me know.

Note that the PCB antenna trace width to get the correct impedence was calculated using JLCPCB's tool, so I cannot recommend ordering this from anywhere else without first redoing said calculation and adjusting the width appropriately.

Disclaimer: I am not a professional RF engineer, I merely followed the schematics on the datasheets for the components as closely as possible. I am fairly confident that it works, but there is always the chance of an error as it has not been tested.
