# Arduino BNC Shield
<!-- ![Image of Arduino BNC Shield](docs/figs/arduino_bnc.jpg) -->
<img src = "docs/figs/arduino_bnc.jpg" width=50% alt=Image of Arduino BNC Shield align="right">

The Arduino BNC Shield is a very simple way to reliably connect an Arduino to one or more BNC 
cables.

Especially in science, it is very common to use an Arduino to trigger a camera or behavioral system or LED from a computer, and most of the commercially available devices that are triggered have BNC input connections. This often leads to flaky and problematic ways of connecting the Arduino to the BNC cable, and thus experimental setups that are delicate.  This simple shield aims to address this problem and give a reliable solution, without any complicated parts or difficult soldering. 

## Features
Up to ten BNC ports attached to different pins on the Arduino.  Five of these pins (3, 5, 6, 9, 10) can be used for digital input our output, and all are PWM capable.  The other five (A0 - A4) can be used for reading analog input voltages, as well as also being usable for digital IO. 

There is also a prototyping area with 0.1 inch pitch through holes, in case you want to add any extra parts such as sensors or digital to analog  converters (DACs) or similar. Two of the BNC ports (3 and A4) have jumpers so that the can be easily attached to something in the prototyping area, such as a DAC, instead of to their Arduino pins. See 

## Build Instructions
For most use cases, all you need to do is solder some [0.1 inch male header](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PRPC040SAAN-RC/2775214) onto the shield to connect it to the Arduino, and some [BNC Jacks](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PRPC040SAAN-RC/2775214) to connect your BNC cables. For the header, it can be helpful to start by putting the long side of the headers into an Arduino to hold them, and then putting the shield on top to solder it. If you've never soldered before, don't worry, it's very learnable! There are many great YouTube videos and other guides on the internet to show you how, such as [this one from AdaFruit.](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PRPC040SAAN-RC/2775214)

## Getting one
The Arduino BNC Shield can be ordered easily and cheaply from any PCB board house (such as [pcbway](pcbway.com), [jlcpcb](jlcpcb.com), etc)  using the zipped gerber files in `bnc_shield_pcb/bnc_shield_gerbers.zip`.  Many board houses have a deal for 5 PCBs of this size for under $10 plus shipping. The only other parts you need are an Arduino Uno, some BNC jacks, and some header to connect the shield to the Arduino. The whole thing can then be easily and quickly assembled even by someone with no soldering experience using only a soldering iron and solder.

### Required parts
|Part|Part Number|Supplier Link|
|---|---|---|
|Arduino Uno|A000066 | https://www.digikey.com/reference-designs/en/open-source-mcu-platforms/2481|
|BNC Jack|0731375003 | https://www.digikey.com/en/products/detail/molex/0731375003/1465136|
|Male 0.1 in Header|PRPC040SAAN-RC | https://www.digikey.com/en/products/detail/sullins-connector-solutions/PRPC040SAAN-RC/2775214


### Optional Parts
|Part|Part Number|Supplier Link|
|---|---|---|
|Reset Button| PTS526 SK15 SMTR2 LFS| https://www.digikey.com/en/products/detail/c-k/PTS526-SK15-SMTR2-LFS/10056626|
|Shield Stacking Header| 85|https://www.adafruit.com/product/85 | 