# fancontroller-hardware
fan controller addon board for OLIMEXINO-STM32F3

## Features:

* Controls 3 4-pin PWM fans. One fan output can be changed to a high power PWM pump control-
* Voltage/current measurement of the fans.
* 4 STEMMA QT compatible connectors, usable for temperature sensors.
* 2 Analog inputs.
* SPI FLASH 64Mb 

## Variants:

* 3 fans: populate J7, J9, J10
* 2 fans, 1 pump: populate J8, J9, J10 and add R2

## Errata

|revision|errata|fixed revision|
|--------|------|--------------|
| 1      | D31/32 are swapped on U3 | 2 |
| 1/2    | GND and +3V3 are swapped on J1/2/3/4 | 3 |

## Modification to OLIMEXINO-STM32F3:

Connect VIN on PLATFORM1 to PWR1 pin 2

## License

Copyright alexth4e9f 2021.

This source describes Open Hardware and is licensed under the CERN-OHL-S v2.

You may redistribute and modify this source and make products using it under the terms of the CERN-OHL-S v2 (https://ohwr.org/cern_ohl_s_v2.txt).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.