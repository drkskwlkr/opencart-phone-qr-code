# Phone QR Code for OpenCart
This is a simple OCmod for OpenCart that displays the client's phone number as a QR code within order view to allow easy dialing without retyping. I made it for myself because sometimes I need to talk with a customer when processing their order, and it has always been a pain for me to squint at the monitor and type the number by hand.

By showing the number in a machine-friendly format, I can now scan the phone number with my own smartphone and be sure I get it right.
The code should be compatible with all OC 2.x and 3.x branches; it was tested on OC 2.1.0.2, OC 2.3.0.2 and OC 3.0.2.0.

# Installation
## OpenCart 2.x
- Download https://github.com/drkskwlkr/opencart-phone-qr-code/blob/master/PhoneQR.ocmod.xml
- Upload it via Extension installer
- Refresh the mod cache.

## OpenCart 3.x
- Download https://github.com/drkskwlkr/opencart-phone-qr-code/blob/master/install.xml
- ZIP it locally and name the archived file `phoneqr.ocmod.zip`
- Upload said ZIP file via Extension Installer
- Refresh the mod cache (Extensions &rarr; Modifications &rarr; Refresh)
- Refresh the twig cache (Dashboard &rarr; Blue Cogwheel (Developer settings) &rarr; Refresh Theme)

## Result
![You should get something like this:](https://i.imgur.com/VDiZ0y1.png)

# Removal
If not happy with this extension for whatever reason, just remove it from Extension Manager and refresh the mod cache (and the twig cache inside OC3.x).
