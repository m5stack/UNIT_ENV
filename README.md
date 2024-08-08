# M5Unit - ENV

## Overview

### SKU:U001 & U001-B & U001-C & U090 & U053-B & U053-D & U103

Contains M5Stack-**UNIT ENV & Hat ENV & UNIT BPS & UNIT CO2** series related case programs.

ENV is an environmental sensor with integrated SHT30 and QMP6988 internally to detect temperature, humidity, and atmospheric pressure data.

BPS is a barometer unit, which integrates the Bosch BMP280 pressure sensor to measure atmospheric pressure and estimate the altitude.

BPS(QMP6988) Unit is a barometer unit that uses QMP6988 barometric pressure sensor to measure atmospheric pressure and altitude estimation

CO2 is a photoacoustic Carbon Dioxide (CO2) Unit that will tell you the CO2 PPM (parts-per-million) composition of ambient air.

## Related Link

- [Unit ENVIV - Document & Datasheet](https://docs.m5stack.com/en/unit/ENV%E2%85%A3%20Unit)
- [Unit ENVIII - Document & Datasheet](https://docs.m5stack.com/en/unit/envIII)
- [Unit ENVII - Document & Datasheet](https://docs.m5stack.com/en/unit/envII)
- [Unit ENV - Document & Datasheet](https://docs.m5stack.com/en/unit/env)
- [Hat ENVIII - Document & Datasheet](https://docs.m5stack.com/en/hat/hat_envIII)
- [Hat ENVII - Document & Datasheet](https://docs.m5stack.com/en/hat/hat_envII)
- [Unit BPS - Document & Datasheet](https://docs.m5stack.com/en/unit/bps)
- [Unit BPS(QMP6988) - Document & Datasheet](https://docs.m5stack.com/en/unit/BPS(QMP6988))
- [Unit CO2 - Document & Datasheet](https://docs.m5stack.com/en/unit/co2)

## Required Libraries:

- [Adafruit_BMP280_Library](https://github.com/adafruit/Adafruit_BMP280_Library)
- [Adafruit_Sensor](https://github.com/adafruit/Adafruit_Sensor)
- [Sensirion I2C SCD4x](https://github.com/Sensirion/arduino-i2c-scd4x)
- [Sensirion I2C SHT4x](https://github.com/Sensirion/arduino-i2c-sht4x)
- [Sensirion Core](https://github.com/Sensirion/arduino-core)

## License

- [M5Unit-ENV - MIT](LICENSE)


---
## M5UnitUnified
The M5UnitUnified version of the library is located under [src/unit](src/unit).  
M5UnitUnfied has a unified API and can control multiple units via PaHub, etc.

### Required Libraries:

- [M5UnitUnified](https://github.com/m5stack/M5UnitUnified)
- [M5Utility](https://github.com/m5stack/M5Utility)
- [M5HAL](https://github.com/m5stack/M5HAL)

### Examples
See also [examples/UnitUnified](examples/UnitUnified)

### Doxygen document
If you want to generate documents on your local machine, execute the following command

```
bash docs/doxy.sh
```

It will output it under docs/html  
If you want to output Git commit hashes to html, do it for the git cloned folder.

#### Required
- [Doxyegn](https://www.doxygen.nl/)
- [pcregrep](https://formulae.brew.sh/formula/pcre2)
- [Git](https://git-scm.com/) (Output commit hash to html)
