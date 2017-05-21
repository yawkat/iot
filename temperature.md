---
title: temperature
---

## temperature

Temperature readings are done using 1wire [DS 18B20](https://www.reichelt.de/ICs-CA-HV-/DS-18B20/3/index.html?ACTION=3&LA=446&ARTICLE=58169&GROUPID=7209&artnr=DS+18B20) sensors soldered onto [arw/tempsens](https://gitlab.cs.fau.de/arw/tempsens) PCBs. I printed these boards at [the local FabLab](http://fablab.fau.de/) which has a PCB printing setup. arw/tempsens also includes schematics for a 3d-printed casing, but I do not use this at the moment.

You could also solder the sensor directly to the plug, but this is more fragile and more difficult.

![Temperature sensing module](images/temp_sensor.png)

You need to be very careful with the direction of the sensor. Soldering it the wrong way around will heat it up a lot and it could potentially break.

See [software](software.html) for details on how data is read.