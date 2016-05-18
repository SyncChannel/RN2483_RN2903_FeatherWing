# RN2483_RN2903_FeatherWing

This FeatherWing adds a Microchip RN2483 or RN2903 LoRaWAN module to Adafruit Feather. It also includes a power LED and an LED connected to GPIO10 of the RN module for debugging or status indication. The parts values are shown in the schematic.

This PCB design is tested and functional. BUT! I DO NOT recommend that you use it. The width of the module and the spacing of the Feather headers prevents a proper footprint for the RN module from being used. The pads are very small and very close to the headers. Even with a small iron tip, it is extremely difficult to hand solder. You MUST check carefully for bridges between the castellations of the module and header pins with magnification after soldering it.

Upon request, I have uploaded the Eagle files to this repo. I will not be doing a blog post article on this one.



Dan Watson

syncchannel.blogspot.com
