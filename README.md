# Gigabyte B450M DS3H OpenCore 0.6.1
* Ryzen 3 3100
* XFX Radeon RX 580 GTS XXX 8GB
* 8GB(2x4) Corsair Vengeance LPX 3000MHz CL16

# Working:
* Everything I tested.

# Partially broken:
* The 4 USB3.1 ports from the motherboard(XHC0) breaks sleep if USB2.0 device is plugged in.
My workaround: Disabled USB2.0 property of these ports from AMD-USB-Map.kext, so only USB3.x devices work in these ports.
* GPU performance takes a hit when using iMacPro1,1(current SMBIOS) or MacPro7,1.
Using iMac18,3 for example increases performance but DRM is broken.