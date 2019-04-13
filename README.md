# Mac-switch-rcm-payload-pusher
While your switch is in rcm mode run this .py file with the .bin file you want to push to inject the payload.
**
Dependencies
**
- Python 3 https://www.python.org/download/releases/3.0/
- libusb https://github.com/libusb/libusb
- pyusb https://github.com/pyusb/pyusb
- tkinter https://tkdocs.com/tutorial/install.html
**

USAGE
-put your switch into rcm mode guides on how to do that here:https://nh-server.github.io/switch-guide/user_guide/entering_rcm/
-have your switch plugged into a usb 2.0 port(usb 3.0 works but it is unstable at the moment so dont come yelling at me when it breaks)
-have your payload.bin file located in the same folder as macpayloadpusher.py
-run macpayloadpusher.py
- your switch will now boot into the custom firmware corresponding to the payload.bin file you pushed

Included below are Kosmos , hekate and Atmosphères directories  
 https://github.com/AtlasNX/Kosmos/releaases/tag/v12.0.1
https://github.com/CTCaer/hekate/releases
https://github.com/Atmosphere-NX/Atmosphere/releases/tag/0.8.7
