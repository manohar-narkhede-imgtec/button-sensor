#Button Sensor Application

This application registers Flow, Flow Access and Digital Input object to Flow server and sends Button press events.

How To Compile

Assuming you have creator-contiki source code with directories constrained-os, packages/button-sensor, packages/libobjects and packages/AwaLWM2M

To build with TI CC2520 6lowpan driver
```
$ cd button-sensor
$ make TARGET=mikro-e USE_CC2520=1
```

To build with Cascoda CA8210 6lowpan driver
```
$ cd button-sensor
$ make TARGET=mikro-e USE_CA8210=1
```

This will generate hex file which can be flashed onto the MikroE clicker.
