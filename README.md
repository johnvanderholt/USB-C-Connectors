# USB-C-Connectors
Various cheap USB-C connectors from LCSC for KiCad. Brief [rundown of the USB standards here](https://flashgamer.com/blog/comments/usb-type-c-and-usb-2.0-3.0-3.1-3.2) and details on [how to use these boards here.](https://flashgamer.com/blog/comments/implementing-usb-type-c-and-usb-3-1)

# Changes
This is a stripped down fork of the original project, condensed down to just the footprints.
 
### Footprints
Library with footprints for low priced Type C & USB3 connectors and alternates.

Compatible part numbers:
- TYPE-C-31-M-17 from Korean Hroparts Elec @ LCSC
- USB4125-GF-A from GCT @ Digikey

### USB-C-USB-2.0
Simple Breakout board exposing all you need for USB 2.0 using a Type C connector. Also has room for resistors for CC1 & CC2 as the power breakout above.

Compatible part numbers:
- TYPE-C-31-M-12 from Korean Hroparts Elec @ LCSC
- USB4105-GF-A from GCT @ Digikey
- CU3216SASDLR010-NH from Civlux @ Digikey

### USB-C-USB-3.2
Breakout board for a fully featured USB 3.2 connector that can be used with a low priced IC for cable detection, orientation, data switching and power settings. 

When using this board, don't forget that to get higher speeds to work, you'll need sub-millimeter precision on your cable lengths. All RX/TX pairs should be the exact same length, just as they are one the PCB. Don't expect SuperSpeed to work if you're using a breadboard for prototyping.

Compatible part numbers:
- U262-241N-4BV60 from XKB Connectivity @ LCSC
- TYPE-C-31-M-04 from Korean Hroparts Elec @ LCSC
- 10137062-00021LF from Amphenol ICC @ Digikey
