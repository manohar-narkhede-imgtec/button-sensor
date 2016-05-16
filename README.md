#Button Sensor Application

This application registers Flow, Flow Access and Digital Input object to Flow server and sends Button press events.

How To Compile

Assuming you have creator-contiki source code with directories constrained-os, packages/button-sensor, packages/libobjects and packages/AwaLWM2M

```
$ cd button-sensor
$ make TARGET=mikro-e
```

This will generate hex file which can be flashed onto the MikroE clicker.

## Revision History
| Revision  | Changes from previous revision |
| :----     | :------------------------------|
| 0.9.0     | External Beta Trial Release    |
