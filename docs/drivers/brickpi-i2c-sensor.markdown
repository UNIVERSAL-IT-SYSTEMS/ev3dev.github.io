---
autogen: This file was automatically generated by kernel-doc-text-to-markdown.py
kernel_version: 3.16.7-ckt26-10-ev3dev-ev3
source_file: drivers/lego/brickpi/brickpi_i2c_sensor.c
title: Dexter Industries BrickPi I2C Sensor Driver
---

A `brickpi-i2c-sensor` device is loaded by the [brickpi] driver when
manually specified by setting the [brickpi-in-port] to `nxt-i2c` mode and
writing the device name and address to `set_device`. You can use any one of
the sensors that has the `nxt-i2c-sensor` module from the [list of supported
sensors]. Not all functionality of a sensor may be supported when connected
to a [brickpi-in-port]. For these, you should use input port 5 on the
BrickPi instead.

### sysfs attributes

Devices bound to this driver can be found in the directory
`/sys/bus/lego/drivers/brickpi-i2c-sensor/`. However, these sensors use
the [lego-sensor class] which is where the useful stuff is. Follow the link
for more information.

[brickpi]: /docs/drivers/brickpi-ld
[brickpi-in-port]: /docs/ports/brickpi-in-port
[list of supported sensors]: /docs/sensors#supported-sensors
[lego-sensor class]: ../lego-sensor-class

