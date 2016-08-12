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
0. Download [SD Card Formatter](https://www.sdcard.org/downloads/formatter_4/)
0. Install and run the program
0. Insert the SD card to be formatted
0. Make sure the correct SD card is selected
0. Select `Overwrite Format`
0. Click `Format`

## Download the Operating System
0. Go to [raspberrypi.org](https://www.raspberrypi.org/downloads/raspbian/)
0. Download the `Raspbian Jessie (lite)` version
0. Unzip the downloaded file

## Copy the OS onto the SD Card
Follow these instructions from raspberrypi.org for:

* [linux](https://www.raspberrypi.org/documentation/installation/installing-images/linux.md)
* [mac](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md)
* [windows](https://www.raspberrypi.org/documentation/installation/installing-images/windows.md)

## Setup the hardware and boot
0. Insert the SD card into the raspberry pi
0. Attach to a monitor with the HDMI cable
0. Attach a USB keyboard
0. Hardwire the Pi to your local network with a cat5 cable
0. Plug in the 2A power supply
0. Wait for the login prompt (on screen)

## Login
0. At the login prompt type in: `pi`
0. At the password prompt type in: `raspberry`

## Get the IP address
0. After login, at the prompt type in: `ifconfig`
0. Look for an IP in the local network range (example: 192.168.1.27)

## Configure the OS
[Continue reading](DEVOPS.md) to configure the newly installed Linux Operating System.