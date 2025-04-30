# Arneus diadematus

This file contains the documentation for 3d printer Arneus diadematus
![Check media](media/Anycubic_Mega_Zero.jpeg)

## Asseble Frame
To asseble frame, follow the [Anycubic mega Zero](Frame/mega_zero.pdf) manual

## MCU
### BIGTREETECH SKR3 EZ
![Check media](media/SKR3_EZ_Title.png)
I have chosen this MCU for its array of features

### Connecting MCU
follow diagram given in the [manual](MCU/BIGTREETECH%20SKR%203%20EZ%20user%20manual.pdf)
![Check media](MCU/BIGTREETECH%20SKR%203%20EZ%20V1.0-PIN.pdf)

## Configurations

### Klipper Configs
#### Calibrations
- Calibrate heaters
```sh
PID_CALIBRATE HEATER=extruder TARGET=200
```
```sh
PID_CALIBRATE HEATER=heater_bed TARGET=60
```

after each calibration runn:
```sh
SAVE_CONFIG
```

### MCU Config

### Mainsail Config


