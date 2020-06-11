# Pi2Jamma

This repository describe how to setup a raspberrypi + a Pi2Jamma card.

## References

Raspberry Pi 3 B+: https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/
Pi2Jamma card: http://www.smallcab.net/pi2jamma-raspberry-p-1725.html

## Install OS

We're going to use recalbox 6.1.1 DragonBlaze.

1. Get the rpi3 image here: https://archive.recalbox.com/
2. Burn the image onto your SD card with your favorite tool, I'm using dd.
3. Plug the SD card into the Pi and switch it on.

## Connect to the Pi

From macOS you can easily ssh into the Pi by setting your computer as dhcp server and linking them via ethernet.

See [dhcp/](dhcp).

## Configure video

Video resolution is handled by hdmi_timings directive in the /boot/config.txt file.

See [video/](video).

## Configure audio

Plug the jack from the RPi into the Pi2Jamma jack port.

## Configure joypads

tbd

# Roms

tbd
