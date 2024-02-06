# About

A tool for viewing and setting the Bluetooth address a DualShock 4 controller is currently paired with.

# Dependencies

HID API https://github.com/signal11/hidapi

# Supported Platforms
* Linux

# Building and using

``` bash
git clone https://github.com/SveinIsdahl/PS4-controller-pairer
cd PS4-controller-pairer
git clone https://github.com/signal11/hidapi
gcc -o PS4pair main.c -lhidapi-libusb
./PS4pair                    #Reads address from PS4 controller
./PS4pair xx:xx:xx:xx:xx:xx  #Adds given address to PS4 controller to pair with
```
