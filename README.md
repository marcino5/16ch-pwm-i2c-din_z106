# PCB 16xPWM i2c
This repository contains KiCAD files. This is an expansion module containing 16 PWM 12-24V outputs. The circuit consists of 16 N-Channel MOSFETs with a load capacity of 10A per channel controlled by a 12-bit LED controller PCA9685PW with an I2C interface. The circuit is not adapted to the maximum current, and for higher currents it is necessary to tin the exposed plus path. In my home configuration with ESPHome it works with 4 meter LED strips per channel and I did not observe any heating of the paths.

![alt text](https://github.com/marcino5/16ch-pwm-i2c-din_z106/blob/main/pcv_view.png?raw=true)



The PCB is designed to fit in a commonly available DIN rail housing.
