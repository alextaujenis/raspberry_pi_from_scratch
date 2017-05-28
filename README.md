# How to build a new Raspberry Pi from scratch
Go shop for a Raspberry Pi and some accessories:

* Raspberry Pi 3 Model B (is the [latest](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/))
* Raspberry Pi case
* 2A power supply
* MicroSD Card
* HDMI cable
* USB Keyboard
* Cat5 Network Cable

## Prepare the SD Card
1. Download [SD Card Formatter](https://www.sdcard.org/downloads/formatter_4/)
1. Install and run the program
1. Insert the SD card to be formatted
1. Make sure the correct SD card is selected
1. Select `Overwrite Format`
1. Click `Format`

## Download the Operating System
1. Go to [raspberrypi.org](https://www.raspberrypi.org/downloads/raspbian/)
1. Download the `Raspbian Jessie (lite)` version
1. Unzip the downloaded file

## Install the Operating System onto the SD Card
Click on _your_ operating system (below) that downloaded the file for specific instructions next.

* [Windows](https://www.raspberrypi.org/documentation/installation/installing-images/windows.md)
* [Mac](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md)
* [Linux](https://www.raspberrypi.org/documentation/installation/installing-images/linux.md)

## Setup the hardware and boot
1. Insert the SD card into the raspberry pi
1. Attach to a monitor with the HDMI cable
1. Attach a USB keyboard
1. Hardwire the Pi to your local network with a cat5 cable
1. Plug in the 2A power supply
1. Wait for the login prompt (on screen)

## Login
1. At the login prompt type: `pi`
1. At the password prompt type: `raspberry`

## Enable SSH
1. At the prompt type: `sudo raspi-config`
1. Select `Interfacing Options`
1. Navigate to and select `SSH`
1. Choose `Yes`
1. Select `Ok`
1. Choose `Finish`

## Get the IP address
1. At the prompt type: `ifconfig | grep inet`
1. Look for an IP in the local network range (example: 192.168.1.27)

## Configure the OS
[Continue reading](DEVOPS.md) to configure the newly installed Operating System.