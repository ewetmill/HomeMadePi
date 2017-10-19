# HomeMadePi
Home Automation With a Raspberry Pi Zero W's.  The aim is to guide the DIYer to be able to fairly easily create home automation solutions while keeping the hardware component's affordable.

Configuration is done through an XML file, but the plan is to eventually add a UI for configuring devices.  The configuration identifies the types of devices, the pins that control the device, and the pins attached to various sensors.

## Homekit
This project allows connecting devices to homekit using Raspberry Pi Zero W's connected to the home's wifi.  The ability to use Siri for controlling and coordinating devices makes this project very desirable to DIYers.

Homekit presents a requires that the user types a pin that the device presents.  The XML file can be configured with a hard coded PIN or to generate a PIN.  If a PIN is generated, the device will need a way to present the PIN to the user to be entered on the mobile device.  An OLED screen for the Pi Zero can be used, like this one: https://learn.adafruit.com/adafruit-pioled-128x32-mini-oled-for-raspberry-pi

### Garage Door Opener
The goal of the Garage door opener is to be able to open and close a garage door using Homekit with a Pi Zero W and associated accessories not to exceed $50 USD.
