# Introduction

This repo contains a skeleton esphome config for the Hosyond ESP32-S3 Touchscreen Module, 2.8" 240x320 IPS LCD EPS32 Display with WiFi Bluetooth Capacitive Touch Screen.
The text on the back of the board reads:

> 2.8" LCD Display
> ESP32-S3 240x320
> Capacitive Touch

And might be listed as ES3C28P or ES3N28P

Lots of technical details about the board can be found
[here](https://www.lcdwiki.com/2.8inch_ESP32-S3_Display)

It's available [here](https://www.amazon.com/dp/B0FKG7WRWV) from Amazon, [here]
(https://www.ebay.com/itm/376660193185) on Ebay, etc.

# Home Assistant and ESPHome

[ESPHome](https://esphome.io/) is a plugin for [Home Assistant](https://www.home-assistant.io/) which allows you to write custom firmware
for ESP based boards which are then integrated automatically with Home Assistant.

# What is in this repo?

This is a skeleton of a config for this board demonstrating the basic
requirements to get the board working with home assistant. I've tested most of
the functionality, and the only thing I've be unable to get working is the
microphone. 

# How to use this repo

 You will need Home Assistant and ESPHome setup.

 # Visit web.esphome.io and provision this board
 # Pair it to your WIFI network (you might have to re-provision it multiple times to get it to work)
 # Visit your ESPBuilder page and your board should show up as available to be added, add it.


# What the board looks like:

This repo is for this board:

![Back of board](https://github.com/celer/esphome_esp32-s3-2.8-display/blob/main/images/board_front.jpg)
![Back of board](https://github.com/celer/esphome_esp32-s3-2.8-display/blob/main/images/board_back.jpg)




