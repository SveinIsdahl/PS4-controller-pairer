# About

A tool for viewing and setting the Bluetooth address a DualShock 4 controller is currently paired with. Based on <https://github.com/user-none/sixaxispairer>, which is designed for Sixaxis controllers, with a couple quick and dirty hacks on top.


# Dependencies

HID API (http://www.signal11.us/oss/hidapi/). macOS users (i.e. `brew install hidapi`), check the comment in main.c.


# Supported Platforms

* Windows
* Mac
* Linux


# Building

``` bash
$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./bin/ds4pairer
$ ./bin/ds4pairer xx:xx:xx:xx:xx:xx
```
