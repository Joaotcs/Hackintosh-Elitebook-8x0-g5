Forked from https://github.com/kecinzer/hpelitebook850g5-opencore
Using on a Elitebook 830 g5 with touchscreen, with fenvi BCM94360NG wifi card, 256gb NVME ssd, 8350u CPU, with working smart card reader.

Differences from kecinzer build:

1- Additional IRQ conflict fixes (prevents problems) - not obligatory;

2- Aditional .aml file for touchscreen (SSDT-TPL0.aml file and active on config.plist) - delete file and edit config.plist if you don't have it.

3- Device Properties with fix for HDMI and USB-C video output, as well as audio spoof;

4- USB mapping for fully working ports: smart card reader, camera, usb's, thunderbolt, bluetooth and also dock station!

5- Opencanopy for better GUI on boot selection.

Edit config.plist with your own PLATFORMINFO

And that's it for now ;) The rest please go see on the original github.
