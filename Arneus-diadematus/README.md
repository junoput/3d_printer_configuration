# Arneus diadematus

This file contains the documentation for 3d printer Arneus diadematus
![Check media](media/Anycubic_Mega_Zero.jpeg)

## Asseble Frame
To asseble frame, follow the [Anycubic mega Zero](Frame/mega_zero.pdf) manual

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


