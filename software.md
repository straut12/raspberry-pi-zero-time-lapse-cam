# Software Installation

If you are using the optional Blinkt, you will need to install the library code on your Raspberry Pi Zero, which requires an internet connection.

You can either:
1) Connect the Raspberry Pi Zero to the internet using a USB to Ethernet dongle
2) If you have a Raspberry Pi with an internet connection you could put your SD card into that to install the libraries, then transfer it back to the Raspberry Pi Zero

Once you are connected to the internet, run the following commands in the terminal (pressing y/n when prompted):

```bash
curl -sS get.pimoroni.com/blinkt | bash
sudo reboot
```
More information can be found on the [Getting started with Blinkt](https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-blinkt) page on the Pimoroni website.